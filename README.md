# 慌慌の花園｜整合版

本整合版以同一個入口切換兩個既有網站，並以 iframe 載入原網站，避免重製或覆寫原本的版面、字體、背景圖片、動畫、搜尋與資料載入程式。

## 整合內容

- 方方歌單：https://lionliontomato.github.io/fang-fang/
- 慌慌の存鑽存歌：https://lionliontomato.github.io/sing-MoneyFang/
- 兩個原網站的 Google 試算表、讀取程式及更新機制均維持獨立。
- 兩個原網站的 favicon 都是 🌸；整合首頁也沿用相同圖示。
- 第二個網站在第一次切換時才載入，避免一進站就同時讀取兩份資料。

## GitHub Pages 部署

1. 下載並解壓縮 ZIP。
2. 建立新的 GitHub Repository（建議設為 Public）。
3. 將解壓縮後的 `index.html` 與 `README.md` 上傳到 Repository 根目錄。
4. 開啟 `Settings` → `Pages`。
5. Source 選 `Deploy from a branch`，Branch 選 `main`，資料夾選 `/(root)`，按 `Save`。
6. 等待 GitHub Pages 發布完成後，開啟新網站測試兩個切換按鈕。

## 注意事項

- 原本兩個 GitHub Pages 網站必須持續公開且可正常使用，整合入口才能載入它們。
- 請勿刪除或改名原本兩個 Repository，也不需要搬動或合併 Google 試算表。
- 本整合版不修改原網站程式碼；原網站日後更新，整合入口載入的內容也會同步呈現。
