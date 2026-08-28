# 2026-08 Hermes Skills 搜尋原始結果

## 搜尋目標
- GitHub Trending — 找 hermes-agent 相關 repo 的 star 增速

---

## 方向1：GitHub Trending ✅ 有效

### 主要資料來源
| 來源 | URL |
|------|-----|
| agents-radar 每日趨勢報告 | https://github.com/duanyytop/agents-radar/issues |
| Hermes Atlas 生態系地圖 | https://hermesatlas.com/ |
| awesome-hermes-agent 清單 | https://github.com/0xNyk/awesome-hermes-agent |

### Hermes 核心數據
- NousResearch/hermes-agent：**237K+ ⭐**，單日最高 +7,454 stars（2026-04）
- 目前穩定每日 +1,178 stars
- v0.20.6（2026-08），MIT License

### 值得關注的 Trending Repo（2026-08 快照）

| Repo | Stars | 單日增幅 | 分類 |
|------|-------|---------|------|
| NousResearch/hermes-agent | 237K | +1,178 | 核心框架 |
| obra/superpowers | 277K | — | Agentic skills framework |
| multica-ai/multica | — | +1,609 | Managed agents 平台 |
| VoltAgent/awesome-agent-skills | 32K | +602 | 1000+ agent skills 精選 |
| huggingface/ml-intern | — | +1,240 | 自主 ML 工程 agent |
| forrestchang/andrej-karpathy-skills | 207K | — | Claude skills  collections |
| affaan-m/everything-claude-code | 167K | — | Claude Code 效能優化系統 |
| langgenius/dify | 137K | — | 生產級 agentic workflow 平台 |
| open-webui/open-webui | 131K | — | Web UI for LLMs |
| shiyu-coder/Kronos | — | — | 金融市場語言 foundation model |
| mem0ai/mem0 | 52K | — | Agent 通用記憶層 |
| shanraisshan/claude-code-best-practice | — | — | Claude Code 最佳實踐 |

### Hermes Atlas 精選（12 分類，238+ repos）

#### Core & Official

1. NousResearch/hermes-agent
   - 成熟度: production
   - GitHub: 237K ⭐ · 48K forks
   - Repo: https://github.com/NousResearch/hermes-agent
   - 說明：核心框架，唯一內建自我學習迴圈的 AI agent，自動從經驗建立並改進 skills，支援 20+ 訊息平台、6 種執行後端、MCP 整合與 cron 排程。
   - 對你有意義的：你現在整個系統的核心，了解其生態系有助發現更多整合可能。
   - 需要：Python 3，Hermes Agent v0.20+

2. NousResearch/hermes-agent-self-evolution
   - 成熟度: beta
   - GitHub: 5.1K ⭐ · 423 forks
   - Repo: https://github.com/NousResearch/hermes-agent-self-evolution
   - 說明：使用 DSPy + GEPA（Genetic Evolution of Prompt Architectures）做自我優化，讓 agent 能自動改進自己的 prompts 和行為。
   - 對你有意義的：長期可提升 Hermes 對你工作流程的理解與執行效率。
   - 需要：Hermes Agent + DSPy 環境

3. NousResearch/autonovel
   - 成熟度: beta
   - GitHub: 1.5K ⭐ · 89 forks
   - Repo: https://github.com/NousResearch/autonovel
   - 說明：端到端長篇小說生成 pipeline，可自動產出 10萬+ 字的小說。
   - 對你有意義的：創意寫作相關，暫無直接價值。
   - 需要：Hermes Agent

4. NousResearch/hermes-paperclip-adapter
   - 成熟度: beta
   - GitHub: 1.8K ⭐ · 103 forks
   - Repo: https://github.com/NousResearch/hermes-paperclip-adapter
   - 說明：將 Hermes 作為受管理的員工接入 Paperclip 公司系統，對接任務管理與治理框架。
   - 對你有意義的：企業級工作流整合，暫不符合你的使用場景。
   - 需要：Paperclip 公司帳號

5. NousResearch/Hermes-Function-Calling
   - 成熟度: production
   - GitHub: 1.4K ⭐ · 124 forks
   - Repo: https://github.com/NousResearch/Hermes-Function-Calling
   - 說明：Hermes LLM 模型的 function calling 範例與訓練資料集。
   - 對你有意義的：底層模型研究資料，暫無直接用途。
   - 需要：無

6. NousResearch/atropos
   - 成熟度: beta
   - GitHub: 1.3K ⭐ · 78 forks
   - Repo: https://github.com/NousResearch/atropos
   - 說明：RL 訓練框架，用於在真實 agent 軌跡上微調 tool-calling 模型。
   - 對你有意義的：模型訓練相關，暫無直接用途。
   - 需要：Tinker API

#### Workspaces & GUIs

7. nesquena/hermes-webui
   - 成熟度: production
   - GitHub: 17.6K ⭐ · 1.2K forks
   - Repo: https://github.com/nesquena/hermes-webui
   - 說明：網頁/手機上使用 Hermes Agent 的最佳方式，提供聊天介面、記憶瀏覽器與設定面板。
   - 對你有意義的：可作為你目前 Telegram 之外的另一個遠端存取介面。
   - 需要：Hermes Agent 運行中

8. outsourc-e/hermes-workspace
   - 成熟度: production
   - GitHub: 6.5K ⭐ · 412 forks
   - Repo: https://github.com/outsourc-e/hermes-workspace
   - 說明：原生網頁工作區，含聊天、終端機、記憶瀏覽器、skills 管理與 inspector 面板。
   - 對你有意義的：功能完整，適合需要視覺化介面管理 Hermes 的場景。
   - 需要：Node.js 部署環境

9. fathah/hermes-desktop
   - 成熟度: production
   - GitHub: 14K ⭐ · 890 forks
   - Repo: https://github.com/fathah/hermes-desktop
   - 說明：桌面伴侶 client，支援安裝、設定與聊天，跨平台。
   - 對你有意義的：桌面應用介面，適合不習慣 CLI 的場景。
   - 需要：Electron 或原生支援

10. farion1231/cc-switch
   - 成熟度: production
   - GitHub: 129K ⭐ · 8.4K forks
   - Repo: https://github.com/farion1231/cc-switch
   - 說明：跨平台 all-in-one manager，支援 Claude Code、Codex、OpenCode、OpenClaw、Helios、GitHub Copilot、Agent、MCP 等多種 agent CLI。
   - 對你有意義的：未來若使用多個 agent，可統一管理切換。
   - 需要：無特殊依賴

11. EKKOLearnAI/hermes-studio
   - 成熟度: production
   - GitHub: 10.5K ⭐ · 732 forks
   - Repo: https://github.com/EKKOLearnAI/hermes-studio
   - 說明：網頁儀表板，含多平台 chat、工作階段管理、排程任務、使用分析與頻道設定（Telegram、Discord、Slack、WhatsApp）。
   - 對你有意義的：可集中管理所有訊息平台的訊息與排程，與你現有 Telegram 高度相關。
   - 需要：Node.js + Hermes Agent

#### Skills & Skill Registries

12. mukul975/Anthropic-Cybersecurity-Skills
   - 成熟度: production
   - GitHub: 30.9K ⭐ · 2.1K forks
   - Repo: https://github.com/mukul975/Anthropic-Cybersecurity-Skills
   - 說明：754 個結構化資安 skills，按 MITRE ATT&CK、NIST CSF 2.0、ATLAS、D3FEND 與 NIST AI RMF 映射。
   - 對你有意義的：可強化 Hermes 的資安威脅辨識與應變能力。
   - 需要：Hermes Agent 相容 agentskills.io

13. wondelai/skills
   - 成熟度: production
   - GitHub: 2K ⭐ · 209 forks
   - Repo: https://github.com/wondelai/skills
   - 說明：商業/行銷/UX/編碼框架技能庫，基於暢銷書方法論（Synergy、SMART、AARRR、RACE 等），62 個 skills + 12 個互動式導引流程。
   - 對你有意義的：彌補 TDD、系統化偵錯、技術債管理等工程技能。
   - 需要：無特殊依賴

14. Agents365-ai/drawio-skill
   - 成熟度: beta
   - GitHub: 7.9K ⭐ · 534 forks
   - Repo: https://github.com/Agents365-ai/drawio-skill
   - 說明：用自然語言描述生成 draw.io 圖表，支援流程圖、架構圖、UML 等。
   - 對你有意義的：可快速產生技術文件所需的架構圖表。
   - 需要：draw.io 或瀏覽器

15. romanescu11/hermes-skill-factory
   - 成熟度: beta
   - GitHub: 540 ⭐ · 71 forks
   - Repo: https://github.com/Romanescu11/hermes-skill-factory
   - 說明：元 skill，自動觀測工作流程並提議將重複流程轉成可重用 skill，支援 /skill-factory propose 手動觸發。
   - 對你有意義的：自動化積累你個人生態系的 skills。
   - 需要：Hermes Agent v2026.3+

16. mohitagw15856/pm-claude-skills
   - 成熟度: beta
   - GitHub: 30K ⭐ · 1.8K forks
   - Repo: https://github.com/mohitagw15856/pm-claude-skills
   - 說明：822 個專業專案管理 skills，可直接在 Hermes 與 Claude Code 使用。
   - 對你有意義的：豐富的 PM 技能庫，適合建立系統化工作流程。
   - 需要：Hermes / Claude Code

17. adnw-vinc/hermes-nextcloud
   - 成熟度: beta
   - GitHub: 91 ⭐ · 5 forks
   - Repo: https://github.com/adnw-vinc/hermes-nextcloud
   - 說明：Nextcloud 橋接，支援 WebDAV 檔案管理、Nextcloud Notes、CalDAV 日曆/任務、CardDAV 聯絡人。
   - 對你有意義的：若有自架 Nextcloud，可與 Hermes 整合統整資料。
   - 需要：Nextcloud 環境 + App Password

18. Shine8592/china-briefing
   - 成熟度: beta
   - GitHub: 1.3K ⭐ · 87 forks
   - Repo: https://github.com/Shine8592/china-briefing
   - 說明：多尺度中文資訊簡報生成器，從全球到街頭等級的新聞分析，含品質門檻與 AI 分析。
   - 對你有意義的：自動化生成中文新聞摘要，適合你的資訊收集需求。
   - 需要：無特殊依賴

19. ZeroPointRepo/youtube-skills
   - 成熟度: beta
   - GitHub: 557 ⭐ · 38 forks
   - Repo: https://github.com/ZeroPointRepo/youtube-skills
   - 說明：YouTube 字幕、搜尋、頻道與播放清單 skills，支援摘要與內容分析。
   - 對你有意義的：可快速擷取 YouTube 影片內容做研究。
   - 需要：無特殊依賴

20. black-forest-labs/skills
   - 成熟度: beta
   - GitHub: 531 ⭐ · 29 forks
   - Repo: https://github.com/black-forest-labs/skills
   - 說明：FLUX 圖像生成 prompting 指南與 API 整合 skills。
   - 對你有意義的：若需要圖像生成能力可參考。
   - 需要：FLUX API 或本地部署

#### Multi-Agent & Swarms

21. zouroboros-swarm-executors
   - 成熟度: experimental
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/zouroboros/swarm-executors
   - 說明：本地 Claude Code 與 Hermes 的 handoff 機制，實現多 agent 協同執行。
   - 對你有意義的：未來若需要多 agent 協作可研究。
   - 需要：Claude Code + Hermes

22. bigiron
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/supermodeltools/bigiron
   - 說明：專業 agent 角色分工框架，支援多個專門化 agent 協同工作。
   - 對你有意義的：適合複雜任務拆分與平行處理。
   - 需要：Hermes Agent

#### Memory Providers

23. honcho-self-hosted
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/elkimek/honcho-self-hosted
   - 說明：加強跨工作階段的用戶模型建構，提供更強的長期記憶與偏好學習。
   - 對你有意義的：若需要更強的長期記憶可研究。
   - 需要：Hermes Agent

24. hindsight
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/vectorize-io/hindsight
   - 說明：跨大型歷史紀錄的 retain/recall/reflect 工作流，適合長期專案追蹤。
   - 對你有意義的：可強化回顧與經驗萃取能力。
   - 需要：Hermes Agent

#### Deployment

25. nix-hermes-agent
   - 成熟度: beta
   - GitHub: — ⭐ · — forks
   - Repo: https://github.com/0xrsydn/nix-hermes-agent
   - 說明：NixOS 部署模板，聲明式配置管理。
   - 對你有意義的：若未來需要在 NixOS 環境部署 Hermes。
   - 需要：NixOS / Nix

26. hermes-agent-docker
    - 成熟度: production
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/NousResearch/hermes-agent
    - 說明：官方 Docker 部署方案，隔離環境執行 Hermes。
    - 對你有意義的：Docker 部署簡化環境設定，適合測試新 skills。
    - 需要：Docker

27. hermesclaw
    - 成熟度: beta
    - GitHub: — ⭐ · — forks
    - Repo: https://github.com/AaronWong1999/hermesclaw
    - 說明：WeChat 橋接，可在同一個 WeChat 帳號上同時運行 Hermes Agent 與 OpenClaw。
    - 對你有意義的：WeChat 整合，適合中文社群應用。
    - 需要：WeChat 帳號

---



## 安裝建議優先順序（已評估）

| 順序 | Skill | 成熟度 | Stars | 理由 |
|------|-------|--------|-------|------|
| 1 | RobinBeraud/hermes-skills（finance/fmp） | beta | 9 | 股票 dashboard 直接相關 |
| 2 | wondelai/skills | production | 2K | 生態系最大，工程技能補充 |
| 3 | hermes-skill-factory | beta | 540 | 自動化累積 workflow skills |
| — | winterliu6/hermes-skills | production | 1 | stars 太少，暂缓 |
