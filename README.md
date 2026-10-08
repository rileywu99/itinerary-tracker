# 東京五日散步帖 · itinerary-tracker

日系繪本風的旅遊行程網站，單一 HTML 檔，手機優先、繁體中文。

**線上看：** https://rileywu99.github.io/itinerary-tracker/

- 頂端固定選單、首頁插圖與出發倒數
- 航班卡片（去程／回程）
- 每日行程：日期切換＋時間軸，交通用彩色標籤，重點行程標「必去」
- 住宿資訊、可打勾的待辦清單（打勾即刪除線，存在瀏覽器裡）
- 插圖全用 SVG 手繪並輕輕動；支援「減少動態效果」設定

行程架構參考 [GO TOKYO 東京觀光官方網站〈東京五日行程〉](https://www.gotokyo.org/tc/story/walks-and-tours/tokyo-itinerary/index.html)；時間、交通、航班與住宿為範例資料。

改行程只要編輯 `index.html` 最下方 `<script>` 裡的 `DEPART`、`DAYS`、`TODO` 三個常數。
