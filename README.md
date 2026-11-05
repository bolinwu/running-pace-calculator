# 跑步配速換算器

純前端靜態網站，使用 HTML、CSS、JavaScript 製作，不需要後端、資料庫或建置工具。

## 本機預覽

直接以瀏覽器開啟 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 建立一個新的 repository，例如 `running-pace-calculator`。
2. 將 `index.html` 上傳到 repository 根目錄並 commit。
3. 進入 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 中，將 Source 設為 **Deploy from a branch**。
5. Branch 選擇 `main`，資料夾選 `/ (root)`，按 **Save**。
6. 等待 GitHub Pages 部署完成。網站網址通常會是：
   `https://<你的 GitHub 帳號>.github.io/running-pace-calculator/`

若 repository 名稱是 `<你的 GitHub 帳號>.github.io`，網址則會是：
`https://<你的 GitHub 帳號>.github.io/`

## 計算方式

- 每公里配速（秒） = 400 公尺秒數 × 2.5
- 各距離時間 = 每公里配速 × 距離（公里）

目前距離使用 5、10、21、42 公里整數值。
