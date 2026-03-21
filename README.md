# 台房智選 PRO｜GitHub Pages 版本

這是一個可直接上傳到 GitHub 的靜態單頁網站版本。

## 檔案說明

- `index.html`：主程式，直接由瀏覽器開啟即可使用
- `.nojekyll`：避免 GitHub Pages 套用 Jekyll 處理

## 上傳到 GitHub 的方式

1. 在 GitHub 建立一個新的 repository
2. 將本資料夾內的所有檔案上傳到 repository 根目錄
3. 到 GitHub 的 **Settings → Pages**
4. 在 **Build and deployment** 裡選擇：
   - **Source**：Deploy from a branch
   - **Branch**：`main`（或你的預設分支）
   - **Folder**：`/ (root)`
5. 儲存後，等待 GitHub Pages 發布完成

## 使用方式

- 本專案為靜態網站，不需安裝 Node.js
- 直接開啟 `index.html` 或部署到 GitHub Pages 即可使用

## 注意事項

此版本使用 CDN 載入：
- Tailwind CSS
- React
- ReactDOM
- Babel Standalone
- Lucide Icons

因此：
- 本機開啟時需要網路
- GitHub Pages 線上使用時也需要能連上上述 CDN
