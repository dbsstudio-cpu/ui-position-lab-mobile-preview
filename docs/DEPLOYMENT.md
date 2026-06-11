# GitHub Pages 上版規則

## 目的

將 UI Position Lab 已產生且經 CC 審核的靜態 HTML 總覽與圖片發布到 GitHub Pages，供 Sean 使用手機瀏覽器驗收。

## 上版前檢查

- 確認來源是 UI Position Lab 輸出的靜態結果。
- 確認不含正式使用者或私人資料。
- 確認沒有 API Key、Token、Cookie、密碼或 `.env`。
- 確認 HTML 不會送出、刪除、付款或修改資料。
- 確認所有資源使用相對路徑，可由 GitHub Pages 直接載入。
- 確認頁面清楚標示版本、產生日期與「近似預覽」。

## 發布位置

- 最新結果：`previews/latest/`
- 歷史結果：`previews/YYYY-MM-DD_version/`

推送到 `main` 後，GitHub Actions 會自動部署。不要手動修改 GitHub Pages 產物分支。

## 失敗處理

1. 查看儲存庫的 Actions 頁面。
2. 確認 Pages source 設為 GitHub Actions。
3. 確認 HTML、圖片與 CSS 路徑大小寫一致。
4. 不要用 `file://` 絕對路徑或 Windows 磁碟路徑。
