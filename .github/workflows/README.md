# 模擬位置捷徑

按一下 → 開啟開發人員選項 → 自動捲動並點進「選取模擬位置應用程式」。

## 取得 APK（用 GitHub Actions）
1. 在 GitHub 建立新儲存庫，把本資料夾內容全部上傳（含隱藏的 .github 資料夾）。
2. 到儲存庫的 Actions 頁面，等 "Build APK" 跑完（約 3–5 分鐘）。
3. 點進該次執行，在 Artifacts 下載 app-debug-apk，解壓縮得到 app-debug.apk。

## 使用
1. 安裝 APK，打開 App，按按鈕 → 跳到無障礙設定 → 開啟本 App 服務。
   （Android 13+ 側載若為灰色：設定 > 應用程式 > 本 App > ⋮ > 允許受限設定）
2. 回到 App 再按一次按鈕即可。

若你的手機選項文字不同，修改 AutoScrollService.kt 內的 KEYWORDS。
