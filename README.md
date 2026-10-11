# TeachingMaterials1

繁體中文互動教學教材集，收錄數學、物理、化學、地理、公民、英文與國文共 **7 份**課程。每份播放時間為 **300 秒（5 分鐘）**，採 **9:16（1080 × 1920 設計比例）**直式畫面，透過內嵌 SVG、動畫、中文旁白與分段字幕呈現教材重點。

**[開啟教材首頁](https://isvincent.github.io/TeachingMaterials1/)** — 可依學科或關鍵字尋找課程。

## 課程目錄

| 學科 | 課程 | 資料夾 | 段落 | 主要內容與互動 |
| --- | --- | --- | ---: | --- |
| 數學 | [線性規劃](https://isvincent.github.io/TeachingMaterials1/linear-programming/) | [`linear-programming/`](./linear-programming/index.html) | 12 | 半平面與可行區域、平行線法與頂點法、精油、合金與成績應用；滑桿移動目標線、點選圖形檢查可行解。 |
| 物理 | [摩擦力](https://isvincent.github.io/TeachingMaterials1/friction-lab/) | [`friction-lab/`](./friction-lab/index.html) | 12 | 靜摩擦與動摩擦、斜面與臨界角、疊放物體的加速度；推力與斜面角度滑桿、概念答案揭曉。 |
| 化學 | [化學式與百分組成](https://isvincent.github.io/TeachingMaterials1/chemistry-formulas/) | [`chemistry-formulas/`](./chemistry-formulas/index.html) | 10 | 質量與莫耳數比例、燃燒分析與分子量、同分異構物與官能基；段落重點揭曉、分子式選擇題。 |
| 地理 | [氣候系統](https://isvincent.github.io/TeachingMaterials1/geography-climate/) | [`geography-climate/`](./geography-climate/index.html) | 10 | 氣溫的影響因素、氣壓、風與氣旋、降水類型與季節分配；段落重點揭曉、雨型選擇題。 |
| 公民 | [所有權的物權特性](https://isvincent.github.io/TeachingMaterials1/civics-ownership/) | [`civics-ownership/`](./civics-ownership/index.html) | 10 | 所有權的四項特性、返還、除去與防止請求、物權移轉與法律限制；段落重點揭曉、權利情境選擇題。 |
| 英文 | [The Lady or the Tiger?](https://isvincent.github.io/TeachingMaterials1/english-lady-or-tiger/) | [`english-lady-or-tiger/`](./english-lady-or-tiger/index.html) | 10 | 情節衝突與作者意圖、重點字彙與兩種句型、文本推論與讀後續寫；可點選的兩難圖、字彙句型檢核、反思輸入。 |
| 國文 | [出師表](https://isvincent.github.io/TeachingMaterials1/chinese-chu-shi-biao/) | [`chinese-chu-shi-biao/`](./chinese-chu-shi-biao/index.html) | 10 | 時代背景與三項規諫、古今異義與君臣責任、首尾呼應與 SWOT 分析；字義與寫作檢核、劉禪角色反思輸入。 |

數學與物理各 12 段；其餘五科各 10 段，每段 30 秒。每份皆為五分鐘重點改編，適合教學導入、互動討論及課後複習，未逐題重現整份教材。

## 播放與操作

1. 從首頁選擇課程。**數學與物理**需點擊開始按鈕；**化學、地理、公民、英文與國文**畫面開啟即自動播放，點「開啟旁白」加入配音。
2. 全部課程皆有播放／暫停、重播、旁白開關、進度條和段落選單。互動操作會暫停，完成後可按播放繼續。
3. 旁白採裝置可用的中文語音即時合成，正常語速 `rate = 1`。瀏覽器對有聲自動播放有限制，通常須先點擊啟動。
4. 可用空白鍵播放／暫停。方向鍵在數學與其餘五科用於切換段落；物理則每次前後移動 5 秒。輸入或操作表單時，請優先使用畫面按鈕。

### 功能差異

| 功能 | 數學 | 物理 | 化學／地理／公民 | 英文／國文 |
| --- | --- | --- | --- | --- |
| 動畫圖解與分段字幕 | 有 | 有 | 有 | 有 |
| 主要互動 | 目標線滑桿、圖形點選 | 推力與角度滑桿 | 重點揭曉、選擇題 | 選擇題、文字反思；英文另有可點選兩難圖 |
| 全文逐字稿 | 課程內可開啟 | 以分段字幕呈現 | 可展開、下載 | 可展開、下載 |
| 延伸練習 | 逐字稿視窗附題目與解析 | 概念答案揭曉 | 課程內檢核 | 課程內檢核與反思 |
| 全螢幕按鈕 | 有 | 未提供 | 有 | 有 |

英文課程以中文解說，畫面保留英文原句與句型。英文、國文的反思文字只在目前頁面工作階段保留，**不會上傳**，重新整理頁面後會消失。

### 語音與字幕

使用瀏覽器 Web Speech API；語音不是內嵌預錄音訊，實際聲音與朗讀耗時依裝置而異。若沒有可用中文語音，可先閱讀字幕，或在系統安裝中文語音。播放時間軸固定為 300 秒，較慢語音可能在段落或字幕切換時被截斷。語音是否能離線使用，依裝置服務而定。

## 本機使用

各課程皆是單一 `index.html`，內嵌 CSS、JavaScript、SVG 與教學文字，沒有外部圖片、字型或程式庫依賴。從對應資料夾下載原始 HTML，即可用支援 JavaScript 的現代瀏覽器開啟；也可下載整份儲存庫後開啟根目錄 `index.html`。

需要以本機 HTTP 伺服器瀏覽時，可在儲存庫根目錄執行：

```sh
python -m http.server 8000
```

再開啟 `http://localhost:8000/`。HTML 圖文與互動本身不需要外部依賴；語音服務依裝置支援情況而定。

## 教材來源與改編範圍

- **數學〈線性規劃〉**：《數學（線性規劃）》PDF，印刷頁 6–23；主播放選編頁 8–20。
- **物理〈摩擦力〉**：高中選修物理 2，2-2〈摩擦力〉，頁 60–65。
- **化學〈化學式與百分組成〉**：《化學（化學式與百分組成）》PDF，頁 61–69。
- **地理〈氣候系統〉**：《地理（氣候系統）》PDF，頁 142–151。
- **公民〈所有權的物權特性〉**：《公民（所有權的物權特性）》PDF，頁 109–115。
- **英文〈The Lady or the Tiger?〉**：《英文（The Lady or the Tiger?）》PDF，頁 2–25。
- **國文〈出師表〉**：《國文（出師表）》PDF，頁 148–163。

原始 Drive 連結可在化學、地理、公民、英文與國文課程中找到；數學與物理頁面列有教材及頁碼資訊。圖表以教學概念為主，地理及三國位置示意圖不代表實際測站數據或疆界。

英文保留原作的開放式結局，未將後來的改寫視為原作答案；國文區分原文與教材補充背景。詳細改編與操作說明可參考 [理科／社會科課程說明](./lesson-guide.md) 及 [英文／國文課程說明](./literature-guide.md)。

## 儲存庫結構與部署

```text
TeachingMaterials1/
├── index.html                 # 七科教材首頁與搜尋
├── README.md                  # 課程與使用說明
├── linear-programming/        # 數學：線性規劃
├── friction-lab/              # 物理：摩擦力
├── chemistry-formulas/        # 化學：化學式與百分組成
├── geography-climate/         # 地理：氣候系統
├── civics-ownership/          # 公民：所有權的物權特性
├── english-lady-or-tiger/     # 英文：The Lady or the Tiger?
├── chinese-chu-shi-biao/      # 國文：出師表
├── lesson-guide.md
├── literature-guide.md
├── .nojekyll
└── .github/workflows/pages.yml
```

各課程資料夾皆以 `index.html` 為入口。網站由 GitHub Pages 提供，現有 [部署工作流程](./.github/workflows/pages.yml) 會在推送至 `main` 時發布，也支援手動執行。新增教材時，請同步更新首頁卡片與本 README 的課程目錄，並以相對路徑連結課程。
