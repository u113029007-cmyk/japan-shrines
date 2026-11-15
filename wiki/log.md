# 紀錄

只能往後加，不改舊紀錄。格式見 AGENTS.md 第 14 節。

## [2026-11-16] setup | 建立資料夾結構、AGENTS.md 第三版

## [2026-11-16] setup | 來源規則改為只用中文資料；raw 空白範本照新清單重建，舊範本移到 raw/_unused/

## [2026-11-16] fix | raw/regions/wikipedia-zh-chiiki.md 經使用者同意由 UTF-16 轉為 UTF-8（內容未改動）

## [2026-11-16] fix | 經使用者同意：raw/hachiman/wikipedia-zh-hachiman.docx 的文字轉存為同名 .md（UTF-8，內容未改動）；raw/usa-jingu/wikipedia-zh-usa-jingu.md 由 UTF-16 轉為 UTF-8，並移除範本提示行

## [2026-11-16] fix | 經使用者同意：插圖改名為 images/illust/gassho.png、images/illust/saisen-bako.png（符合命名規則）

## [2026-11-16] fix | 經使用者同意：raw 檔名改為「網站簡稱-主題」格式（7 個檔案，只改名不改內容）

## [2026-11-16] ingest | raw 全部 13 份（regions、hachiman、usa-jingu、inari、tenjin、shinshi、sanpai）
- 新增 wiki/_templates/deity.md、shrine.md、concept.md
- 新增 wiki/deities/hachiman.md、inari.md、tenjin.md（draft）
- 新增 wiki/shrines/usa-jingu.md（draft）
- 新增 wiki/concepts/shinshi.md、sanpai.md（draft）
- raw/regions/wikipedia-zh-chiiki.md 作為 AGENTS.md 第 7.5 節地區表的依據，未另建 wiki 頁
- 發現的不一致：八幡宮數量（4 萬餘座／4 萬 4 千座）；宇佐神宮本殿為國寶或重要文化財（來源互相矛盾），兩者皆已在 wiki 中並列
- 略過的內容：稻荷神條目中動畫、輕小說段落；菅原道真條目中官職年表、詩作；宇佐神宮旅遊文章中宇佐市觀光介紹

## [2026-11-16] ingest | raw/usa-jingu/mlit-usa-jingu.md、raw/usa-jingu/gltjp-usa-jingu.md
- 使用者同意 AI 查證「宇佐神宮本殿是國寶還是重要文化財」
- 觀光廳（政府）與 GLTJP（宇佐神宮監製的官方資訊）都寫本殿為國寶；旅遊網站 japantravel 的「1861 年重建、重要文化財」與其他來源不同，wiki 保留並註明
- 創建 725 年、地位僅次於伊勢神宮，改由官方資訊支持，移除「僅單一旅遊網站資料」標註
- 更新 wiki/shrines/usa-jingu.md、wiki/deities/hachiman.md

## [2026-11-16] publish | index.html、deities/hachiman.html、inari.html、tenjin.html、shrines/usa-jingu.html、concepts/shinshi.html、sanpai.html
- wiki 六頁改為 confirmed 後產生網頁；建立 css/style.css 與三個 _template.html
- 插圖 2 張登記於 images/CREDITS.md（全站插圖 2／20）
- 尚無照片：首頁與神祇頁的意象照片、神使插圖待使用者提供

## [2026-11-16] publish | 全站重新產生（風格加強）
- AGENTS.md 新增第 9.1 節神祇主題色、第 9.2 節和風紋樣；同步補上先前漏掉的中文資料來源規則（第 6、12 節）
- css/style.css 加入主題色、青海波頁首、分隔裝飾、深色頁尾；三個 _template.html 加上主題 class 與分隔裝飾
- shinshi.html、inari.html 的來源名稱更正為 UpToGo

## [2026-11-16] fix | 圖片改名符合命名規則：inari-01.jpg、tenjin-01.jpg、illust/toro.png、illust/shimenawa.jpg、illust/temizu.png（只改名）

## [2026-11-16] publish | 全站重新產生（加入圖片、收錄的神社改為醒目區塊）
- AGENTS.md 新增第 8.2 節「收錄的神社要醒目」、第 10.1 節介紹用圖片、第 10.2 節裝飾用圖片
- 照片 4 張、插圖新增 7 張登記於 images/CREDITS.md（插圖共 9／20）；照片作者與授權待補
