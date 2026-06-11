# UI Position Lab Mobile Preview

UI Position Lab 的獨立手機預覽與驗收通道。

此儲存庫透過 GitHub Pages 發布靜態預覽結果，讓 Sean 可直接使用 iPhone 或 Android 瀏覽器查看 UI Position Lab 產生的比較頁面。

## 定位

- 只發布靜態 UI 預覽與截圖總覽。
- 不執行 Future Capsule 功能測試。
- 不連接正式 API、資料庫、金流或推播服務。
- 不存放帳號、Token、私人訊息或正式使用者資料。
- 不取代 iPhone 真機最終驗收。

## GitHub Pages

推送至 `main` 後，`.github/workflows/pages.yml` 會自動發布整個網站。

網站入口：

`https://dbsstudio-cpu.github.io/ui-position-lab-mobile-preview/`

## 目錄

```text
.
├─ .github/workflows/pages.yml
├─ docs/
│  ├─ DEPLOYMENT.md
│  ├─ MOBILE_TEST_CHECKLIST.md
│  └─ PRIVACY_AND_SAFETY.md
├─ previews/
│  ├─ README.md
│  └─ latest/
│     └─ index.html
├─ .gitignore
├─ index.html
└─ README.md
```

## 目前狀態

部署骨架已建立。UI Position Lab v1 尚未交付，因此 `previews/latest/` 目前是等待頁；第一版工具通過 CC 審核後，再放入可公開的靜態 HTML 與圖片結果。
