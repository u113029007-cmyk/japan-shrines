# 日本神社導覽：從神找神社

先選一位神，再找祂的神社。這是一個用「LLM Wiki」方式維護的靜態網站，介紹日本神社祭祀的神祇、各地的神社，以及神使、參拜方式等概念。

- 網站：https://u113029007-cmyk.github.io/japan-shrines/
- 給 AI 的規則：[`AGENTS.md`](AGENTS.md)
- 製作過程的決策紀錄：[`DECISIONS.md`](DECISIONS.md)

## 三層架構

| 層 | 資料夾 | 說明 |
|---|---|---|
| 原始資料 | `raw/` | 使用者蒐集的中文資料，只讀；維基百科放全文，其他網站只放摘錄 |
| 知識整理 | `wiki/` | AI 依 raw 整理的 markdown，每句事實都標來源；`index.md` 是目錄，`log.md` 是時間紀錄 |
| 規則 | `AGENTS.md` | 規定資料夾、命名、頁面格式、來源規則、新增內容的步驟與檢查清單 |
| 網頁 | `index.html`、`deities/`、`shrines/`、`concepts/` | 由 confirmed 的 wiki 頁照 `_template.html` 產生 |

## 怎麼預覽

直接用瀏覽器打開 `index.html`，不需要安裝任何東西。

## 怎麼新增內容

開新對話，對 AI 說：

> 請先讀 AGENTS.md。新增「○○神社」，資料在 raw/○○/……

AI 會照 AGENTS.md 第 13 節的流程：先寫 wiki 給你確認，確認後才產生網頁，並更新目錄和紀錄。

## 圖片與資料出處

- 照片：Wikimedia Commons，出處見 `images/CREDITS.md` 與各頁圖說
- 插圖：いらすとや
- 文字資料來源：見各頁「來源」區塊與 `raw/`
