# AI 寵物美容店模擬器

以香港社區寵物美容店為背景的瀏覽器模擬遊戲。遊戲數字是簡化模型，不代表真實市場或 AI 成效。

遊玩：GitHub Pages 啟用後從此儲存庫的 Pages 網址進入。遊戲進度保存在瀏覽器本機，清除瀏覽器資料可能令存檔消失。

## 修改及重建

`source-code.zip` 包含原始碼、測試和交接文件；解壓後，將儲存庫 `audio` 資料夾複製到 `src/audio`，再執行 `python build.py`。建置輸出為 `dist/standalone.html` 及 `dist/audio`；更新網站時，將前者上傳為根目錄 `index.html`，並保持根目錄的 `audio` 與之同步。遊戲透過網絡載入 Three.js，需要網絡連線。

遊戲沿用原有素材；特殊客圖片和兩首背景音樂的權利詳見 `docs/KNOWN_ISSUES.md`，再次分發或商業使用前應取得相應授權。
