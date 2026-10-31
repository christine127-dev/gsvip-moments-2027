# GSVIP Moments 好時光企劃 · 2027 冠名合作提案

GirlStyle 女生日常 × PressLogic 嘅品牌招商互動 scroll page。純靜態網頁（HTML + CSS + JS），唔使 build。

## 結構

```
index.html          主頁（全部 CSS / JS 已內嵌）
assets/img/         圖片、sticker、蠟印、信封
assets/video/       活動精華片、回顧 post 動態片
.nojekyll           叫 GitHub Pages 唔好用 Jekyll 處理
```

外部資源：GSAP 3.12.5（cdnjs）、Google Fonts（Playfair Display、Noto Serif TC、Noto Sans TC、DM Sans）。

## 上 GitHub Pages

1. 喺 GitHub 開一個新 repository（例如 `gsvip-moments-2027`）。
2. 將呢個資料夾入面所有檔案上傳到 repo 根目錄（包括 `.nojekyll`）。
   - 網頁介面：Add file → Upload files → 拖晒入去 → Commit。
   - 或者用 terminal：
     ```
     git init
     git add .
     git commit -m "GSVIP Moments 2027 scroll page"
     git branch -M main
     git remote add origin https://github.com/<帳戶>/gsvip-moments-2027.git
     git push -u origin main
     ```
3. Repo → Settings → Pages → Source 揀 **Deploy from a branch**，Branch 揀 `main` / `/ (root)` → Save。
4. 大約 1–2 分鐘後，網址會係 `https://<帳戶>.github.io/gsvip-moments-2027/`。

## 出街前要處理

- `[BOOKING_LINK]`：「預約會議」掣嘅連結（例如 Calendly / Google 預約表）。喺 `index.html` 搜尋 `[BOOKING_LINK]` 替換。
- WhatsApp：`wa.me/85259774378`，訊息第一行固定為「【GSVIP Moments 2027 品牌合作查詢】」，ChatBooster 可用呢句做 trigger。
- 數字待確認：4,500+ / 286% / 96%、預計成效（250,000+ 等）。
- 品牌授權：Caudalie 及回顧 album 內其他合作品牌、Cake Party 相關畫面。

## 本地預覽

```
python3 -m http.server 8000
```
再開 `http://localhost:8000`。（直接雙擊 index.html 大部分都得，不過影片喺部分瀏覽器要經 server 先播到。）
