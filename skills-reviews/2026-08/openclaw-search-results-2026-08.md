# 2026-08 OpenClaw Skills 搜尋原始結果

## 搜尋目標
- GitHub Trending — 找 OpenClaw 生態系相關 repo 的 star 增速

---

## 主要資料來源

| 來源 | URL |
|------|-----|
| OpenClaw Radar 生態系每日報告 | https://github.com/Haderach-Ram/openclaw-radar/issues |
| awesome-openclaw 清單 | https://github.com/alvinreal/awesome-openclaw |
| VoltAgent awesome-openclaw-skills | https://github.com/VoltAgent/awesome-openclaw-skills |
| ClawHub 技能市集 | https://clawhub.com |
| OpenClaw 官方 Skills | https://github.com/openclaw/skills |

---

## OpenClaw 核心數據（2026-08-28 快照）

| 框架 | Stars | Open Issues | New Releases |
|------|-------|-------------|--------------|
| **OpenClaw** | 387,851 | 5,727 | 0 |
| Hermes Agent | 237,355 | 36,646 | 1 |
| ZeroClaw | 32,667 | 812 | 0 |
| IronClaw | 12,604 | — | 1 |
| Moltis | 2,839 | — | 1 |

OpenClaw 官方資料：
- v2026.8.1-beta（最新）
- License: MIT
- 官方 GitHub：https://github.com/openclaw/openclaw

---

## OpenClaw 官方專案

1. openclaw/openclaw
   - 成熟度: production
   - GitHub: 387K ⭐ · 81K forks
   - Repo: https://github.com/openclaw/openclaw
   - 說明：核心框架，個人 AI 助理，任何 OS、任何平台。最新 2026.8.x，修復 Discord 即時生命週期問題與 cron 調度器。
   - 對你有意義的：你目前使用的底層系統，了解生態系有助整合。
   - 需要：Node.js 18+

2. openclaw/skills
   - 成熟度: production
   - GitHub: 3.9K ⭐ · 1K forks
   - Repo: https://github.com/openclaw/skills
   - 說明：ClawHub 所有 skills 的完整存檔，支援手動下載。
   - 對你有意義的：可離線瀏覽所有可用 skills。
   - 需要：無

3. openclaw/Peekaboo
   - 成熟度: beta
   - GitHub: 5K ⭐ · — forks
   - Repo: https://github.com/openclaw/Peekaboo
   - 說明：macOS 截圖 CLI 與選用 MCP server，支援本地或遠端 AI 模型的視覺问答。
   - 對你有意義的：螢幕擷取與分析能力。
   - 需要：macOS

4. openclaw/mcporter
   - 成熟度: production
   - GitHub: 4.9K ⭐ · — forks
   - Repo: https://github.com/openclaw/mcporter
   - 說明：TypeScript API 與 CLI，呼叫 MCP servers，可包裝成 cli。
   - 對你有意義的：MCP 協定整合能力。
   - 需要：Node.js

5. openclaw/acpx
   - 成熟度: beta
   - GitHub: 3.1K ⭐ · — forks
   - Repo: https://github.com/openclaw/acpx
   - 說明：無頭 CLI client，適用於狀態性 ACP 工作階段。
   - 對你有意義的：無頭環境下的 ACP 協定支援。
   - 需要：Node.js

6. openclaw/clawhub
   - 成熟度: production
   - GitHub: 9.3K ⭐ · — forks
   - Repo: https://github.com/openclaw/clawhub
   - 說明：官方 skill 目錄與發現中心，49,000+ skills。
   - 對你有意義的：所有 OpenClaw skills 的集中入口。
   - 需要：無

7. openclaw/lobster
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/openclaw/lobster
   - 說明：官方工作流 shell，用於組合工具與可恢復的自動化。
   - 對你有意義的：工作流自動化編排。
   - 需要：Node.js

8. openclaw/gitcrawl
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/openclaw/gitcrawl
   - 說明：本地優先的 GitHub issue 與 PR crawler，用於維護者分類。
   - 對你有意義的：GitHub 資料爬取與分析。
   - 需要：Node.js

---

## Skills 生態系

9. VoltAgent/awesome-openclaw-skills
   - 成熟度: production
   - GitHub: 5.2K ⭐ · — forks
   - Repo: https://github.com/VoltAgent/awesome-openclaw-skills
   - 說明：ClawHub 5,400+ skills 的精選索引，按分類整理，含安全提醒與 VirusTotal 掃描。
   - 對你有意義的：最完整的 OpenClaw skills 精選清單。
   - 需要：無

10. LeoYeAI/openclaw-master-skills
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/LeoYeAI/openclaw-master-skills
    - 說明：精選 1,200+ 最佳 OpenClaw skills，每週更新。
    - 對你有意義的：高品質 skills 精選，適合系統性探索。
    - 需要：無

11. activeloopai/hivemind
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/activeloopai/hivemind
    - 說明：將 agent traces 轉為跨 OpenClaw 與其他 agent runtimes 的可重用 skills。
    - 對你有意義的：工作流技能化，自動化累積經驗。
    - 需要：OpenClaw / Python

12. drakulavich/kesha-voice-kit
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/drakulavich/kesha-voice-kit
    - 說明：開源語音工具包，支援 OpenClaw skill。語音轉文字（25 語言）、文字轉語音（Kokoro + Piper）、語音活動偵測。
    - 對你有意義的：語音互動能力，可做 TTS/STS 應用。
    - 需要：Kokoro / Piper TTS 模型

13. screenpipe/screenpipe
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/screenpipe/screenpipe
    - 說明：本地 24/7 螢幕錄製，支援 OpenClaw、Helios 與其他 agents（YC S26）。
    - 對你有意義的：長期螢幕監控與分析，適用於自動化流程記錄。
    - 需要：本地執行環境

14. agentskillexchange/skills
    - 成熟度: production
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/agentskillexchange/skills
    - 說明：2,000+ 經過安全掃描的 AI agent skills 目錄，支援 Claude Code、Cursor、Codex 與 OpenClaw。
    - 對你有意義的：安全審計過的 skills 清單，降低安裝風險。
    - 需要：無

---

## Dashboards 與控制中心

15. iOfficeAI/AionUi
    - 成熟度: production
    - GitHub: 32K ⭐ · — forks
    - Repo: https://github.com/iOfficeAI/AionUi
    - 說明：跨平台本地 cowork app，支援 OpenClaw、Claude Code、Codex 等多種 coding-agent 生態系。
    - 對你有意義的：統一的視覺化介面，管理多個 agent。
    - 需要：Electron

16. farion1231/cc-switch
    - 成熟度: production
    - GitHub: 129K ⭐ · — forks
    - Repo: https://github.com/farion1231/cc-switch
    - 說明：跨平台 all-in-one manager，支援 Claude Code、Codex、OpenCode、OpenClaw、Helios、GitHub Copilot、Agent、MCP 等。
    - 對你有意義的：未來若使用多個 agent，可統一管理切換。
    - 需要：無特殊依賴

17. dreamwing/clawbridge
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/dreamwing/clawbridge
    - 說明：行動版儀表板，監控工作階段、成本與任務。
    - 對你有意義的：從手機監控 OpenClaw 狀態。
    - 需要：行動裝置

---

## 部署與運維

18. openclaw/clawdinators
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/openclaw/clawdinators
    - 說明：NixOS / AWS 宣告式基礎設施，用於持久化 agent 部署。
    - 對你有意義的：雲端部署自動化。
    - 需要：NixOS / AWS

19. LeoYeAI/openclaw-guardian
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/LeoYeAI/openclaw-guardian
    - 說明：看門狗與自我修復助手，支援 OpenClaw Gateway 運維。
    - 對你有意義的：提升系統穩定性，自動偵錯修復。
    - 需要：Node.js

20. 1Panel-dev/1Panel
    - 成熟度: production
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/1Panel-dev/1Panel
    - 說明：伺服器面板，一鍵部署 OpenClaw。
    - 對你有意義的：伺服器管理與一鍵部署。
    - 需要：Linux 伺服器

---

## 插件與頻道整合

21. m1heng/clawdbot-feishu
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/m1heng/clawdbot-feishu
    - 說明：飛書插件整合，適用於 OpenClaw 生態系。
    - 對你有意義的：飛書平台整合。
    - 需要：飛書帳號

22. onfabric/waclaw
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/onfabric/waclaw
    - 說明：WhatsApp 路由，支援 fleet 部署。可同時作為 OpenClaw 與 Claude Code 插件。
    - 對你有意義的：WhatsApp 整合。
    - 需要：WhatsApp Business API

23. soimy/openclaw-channel-dingtalk
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/soimy/openclaw-channel-dingtalk
    - 說明：釘釘頻道整合。
    - 對你有意義的：釘釘平台整合。
    - 需要：釘釘開發者帳號

---

## Alternative Clients

24. tinyhumansai/openhuman
    - 成熟度: experimental
    - GitHub: 37.5K ⭐ · — forks
    - Repo: https://github.com/tinyhumansai/openhuman
    - 說明：跨平台 OpenClaw 風格助理，Rust 核心 + Tauri 桌面 app，多頻道訊息、知識圖譜記憶、skills 支援。
    - 對你有意義的：Rust 實現的 OpenClaw 風格助理，適合效能敏感場景。
    - 需要：Rust / Tauri

---

## 安裝建議優先順序（已評估）

| 順序 | 項目 | 成熟度 | Stars | 理由 |
|------|------|--------|-------|------|
| 1 | cc-switch | production | 129K | 跨所有主流 agent CLI 統一管理 |
| 2 | AionUi | production | 32K | 視覺化介面，支援 OpenClaw |
| 3 | kesha-voice-kit | beta | — | 語音能力，補充互動方式 |
| 4 | openclaw-guardian | beta | — | 看門狗，提升系統穩定性 |
