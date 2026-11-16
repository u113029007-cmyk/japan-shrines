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

## [2026-11-16] setup | 推送到 GitHub：u113029007-cmyk/japan-shrines（main 分支）
- 新增 README.md（給人看的說明）、.nojekyll（讓 GitHub Pages 原樣發佈）
- 修正 AGENTS.md 第 9 節表格斷行與分隔裝飾寫法（排版修正，規則內容未變）

## [2026-11-16] publish | 照片出處更新
- hachiman-01.jpg：使用者提供 Commons 頁面「File:Sōgyō Hachiman.jpg」，作者不詳、公有領域
- tenjin-01.jpg：作者 Immanuelle（使用者截圖），授權待補
- inari-01.jpg、usa-jingu-01.jpg 找不到下載來源，先從網頁拿掉，檔案保留

## [2026-11-16] ingest | raw/inari/wikipedia-zh-fushimi-inari-taisha.md
- 新增 wiki/shrines/fushimi-inari-taisha.md（draft）：基本資料、由來與歷史、祭神與信仰、境內看點、參拜小提醒、來源
- 更新 wiki/deities/inari.md（改為 draft）：「收錄的神社」加入伏見稻荷大社
- 更新 wiki/index.md：新增神社一行；inari 狀態改為 draft
- 待補資料：無；來源僅一份（中文維基百科），官網中文版尚未收錄

## [2026-11-16] publish | shrines/fushimi-inari-taisha.html
- wiki/shrines/fushimi-inari-taisha.md、wiki/deities/inari.md 改為 confirmed（使用者確認後）
- 新增 shrines/fushimi-inari-taisha.html；deities/inari.html 加入「近畿」區塊卡片，收錄數改為 1；首頁稻荷神收錄數改為 1
- 新增照片 images/fushimi-inari-taisha-01.jpg（作者 Jakub Hałun，CC BY 4.0），登記於 CREDITS.md；Commons 頁面連結待補

## [2026-11-16] publish | 伏見稻荷大社照片、稻荷神照片
- 伏見稻荷大社頁照片的 Commons 連結補上（作者 Jakub Hałun，CC BY 4.0）
- 稻荷神頁與首頁卡片加上照片 images/inari-01.jpg（作者 Hyppolyte de Saint-Rambert，CC BY-SA 4.0）；Commons 頁面連結待補
- 原 images/inari-01.jpg（無來源、未使用）由新照片取代

## [2026-11-16] lint | 檢查新對話測試的結果
- 比對 commit 116f902 與 b44a0ca：測試 AI 新增伏見稻荷大社（wiki、網頁、照片），更新稻荷神頁、首頁、index、log、CREDITS；未動 raw 與其他頁面
- 發現 3 個規則漏洞，經使用者同意補進 AGENTS.md 第 10、15、17 節

## [2026-11-16] publish | 全站重新產生（照片出處補齊）
- 照片出處補齊：tenjin-01.jpg、usa-jingu-01.jpg（Immanuelle，CC BY 4.0）、hachiman-02.jpg（Aruitaro，CC BY-SA 4.0）；inari-01.jpg 的 Commons 網址待補
- 「dazaifu Tenmangu ox.jpg」改回 tenjin-01.jpg；usa-jingu-01.jpg 放回宇佐神宮頁；hachiman-02.jpg 放在八幡神頁神使段落

## [2026-11-16] publish | 補齊稻荷神照片出處、加入牛的插圖
- inari-01.jpg 補上 Commons 頁面：File:Fushimi_Inari-taisha_gerbe_de_céréales.jpg（Hyppolyte de Saint-Rambert，CC BY-SA 4.0）
- 新增插圖 images/illust/ox.png（いらすとや），用在首頁天神卡片、天神頁神使段落、神使頁；插圖共 10／20
- 全站照片出處已無「待補」

## [2026-11-16] publish | 版面微調
- 首頁稻荷神卡片的狐狸照片改為保留上半部
- 首頁神祇卡片、神祇頁「收錄的神社」區塊加上「持續更新中…」預留欄位（AGENTS.md 第 8.1、8.2 節）

## [2026-11-16] publish | 首頁「關於這個網站」、手機版修正
- 首頁新增「關於這個網站」區塊（AGENTS.md 第 8.1 節）
- 手機版表格第一欄不換行；修正神使頁表格中「天神」名稱重複

## [2026-11-16] publish | 插圖排列對齊；DECISIONS.md 補完
- 神使頁、參拜方式頁的插圖改為同樣高度、同樣間距，圖說對齊（只改 css/style.css）
- DECISIONS.md 中「待測試」「待討論」的項目，依測試結果與後續決定補完

## [2026-11-16] lint | 新對話健檢，發現 4 個問題
- 測試 AI 只讀 AGENTS.md 做健檢，列出問題，未修改任何檔案
- 問題：AGENTS.md 提到已不存在的 raw/_unused/；log 用了未定義的 setup、fix 類型；DECISIONS.md #1、#5 未更新；第 13.4 節與第 14 節對健檢是否寫 log 互相矛盾

## [2026-11-16] fix | 依健檢結果修正規則文件
- 使用者已自行刪除 raw/_unused/；AGENTS.md 第 4、6 節刪除相關文字
- AGENTS.md 第 13.4 節：健檢只可在 log.md 加一筆 lint 紀錄；第 14 節：補上 setup、fix 類型，以及 index.md「待建立（候選）」段落的規則
- DECISIONS.md：#1 註明已被 #7 取代、#5 更新進度、新增 #27
- wiki/index.md：新增「待建立（候選）」段落（8 項）
- raw/usa-jingu 的 mlit 網址（/tagengo-db/en/H30-01300.html）是搜尋結果中的多語版頁面網址，保留不改

## [2026-11-16] fix | 更正上方「新對話健檢」紀錄
- 依測試 AI 原始回覆核對：實際列出 8 個問題（需使用者決定 5 個、文件一致性 3 個），不是 4 個
- 「第 13.4 節與第 14 節矛盾」不是測試 AI 發現的，是事後核對時發現
- 未處理、維持現狀：伏見稻荷大社只有 1 份來源；gltjp、mlit 兩份 raw 只有搜尋摘要
