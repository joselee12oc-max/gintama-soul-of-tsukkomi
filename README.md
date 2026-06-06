# 銀魂 Soul of Tsukkomi

這是一個以銀魂角色與搞笑風格打造的網頁遊戲展示專案，包含 18 名角色與多段互動式選角與戰鬥流程。專案以單一 `index.html` 檔案呈現，所有圖片資源已整理至 `images/` 資料夾。

## 專案結構

- `index.html`：遊戲主頁面與所有 JavaScript、CSS 內容。
- `images/`：存放角色圖像與遊戲素材圖片。

## 主要更新

- 將所有 JPG 圖片集中整理至 `images/` 資料夾
- 修正 `index.html` 中的圖片路徑引用
- 新增本 `README.md`，方便專案說明與分享

## 執行方式

1. 下載或克隆專案到本機
2. 使用瀏覽器開啟專案中的 `index.html`
3. 或者使用本機靜態伺服器，例如：
   - `npx http-server .`
   - `python -m http.server 8000`
4. 在瀏覽器開啟 `http://localhost:8000`

## GitHub 上傳

本專案已設定遠端倉庫：`https://github.com/joselee12oc-max/gintama-soul-of-tsukkomi.git`

若本機環境已安裝 Git，請執行：

```bash
git add .
git commit -m "整理圖片資料夾並新增 README"
git push origin main
```

## GitHub Pages

專案已新增 GitHub Pages 部署工作流程：`.github/workflows/pages.yml`

若這份配置成功執行，網站將自動部署到：

`https://joselee12oc-max.github.io/gintama-soul-of-tsukkomi/`

如果你希望，我也可以幫你檢查 Actions 是否通過，或協助你進一步設定自訂網域。
