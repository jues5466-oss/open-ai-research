# OpenClaw 最新動態翻譯

## 1. 修復：隔離外部直接訊息執行政策
- **URL**：https://github.com/openclaw/openclaw/commit/6b41ef311f31de6d2e6693652377aaa9bbb3e472
- **時間**：2026-04-23 00:39 UTC
- **翻譯**：
  將外部直接訊息（DM）的執行政策進行隔離處理，防止外部訊息內容影響內部執行環境的安全邊界。這是一個安全性修復，確保來自外部的訊息無法透過特殊构造繞過執行限制。
- **摘要**：安全修復，隔離外部 DM 的執行政策，避免外部內容干擾內部執行環境。

---

## 2. 功能：新增 xai 即時語音轉寫
- **URL**：https://github.com/openclaw/openclaw/commit/67f09ea87af6f40c123424efa040d55719521651
- **時間**：2026-04-23 00:35 UTC
- **翻譯**：
  新增 xAI 即時語音轉寫功能（realtime transcription）。現在可以透過 xAI 服務實現即時語音轉文字，讓 OpenClaw 能直接在對話中處理語音輸入，無需等待錄音完成再處理。
- **摘要**：新功能，支援 xAI 即時語音轉文字服務。

---

## 3. 修復：說明已安裝插件替換邏輯
- **URL**：https://github.com/openclaw/openclaw/commit/87a64a33f1671347945bf0cec7080acd35d9c23c
- **時間**：2026-04-23 00:24 UTC
- **翻譯**：
  修復插件安裝時的替換邏輯說明文件。當一個插件已安裝在系統目錄後，若使用者在本機再次安裝相同插件，現在會正確處理替換而非忽略安裝。
- **摘要**：修復插件替換邏輯，確保本地安裝能正確覆寫系統預設插件。

---

## 4. 修復：移除無效的 Codex 應用服務層級
- **URL**：https://github.com/openclaw/openclaw/commit/fa43cbfcba8c5c39ff98da751006d26dc75cb7e6
- **時間**：2026-04-23 00:23 UTC
- **翻譯**：
  移除 Codex 應用服務（app-server）中無效的服務層級設定。這些層級在當前架構中已不再被使用，清理這些設定有助於簡化配置並避免混淆。
- **摘要**：清理 Codex app-server 中已廢棄的服務層級設定。

---

## 5. 文件：說明 npm update 行為
- **URL**：https://github.com/openclaw/openclaw/commit/53f388fa83d2fc9fddf8420e002c7cfe5d211b59
- **時間**：2026-04-23 00:29 UTC
- **翻譯**：
  新增文件說明插件系統中 `npm update` 的行為。當使用者在本地對已安裝的插件執行 npm update 時，現在會正確觸發重新載入邏輯，讓更新立即生效。
- **摘要**：文件說明 npm update 插件時會正確觸發重新載入。
