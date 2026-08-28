# 2026-08 Hermes Skills 搜尋原始結果

## 搜尋目標
- 方向1：GitHub Trending — 找 hermes-agent 相關 repo 的 star 增速
- 方向2：社群討論監控 — X/Reddit 上 Hermes 相關熱門討論

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

#### Core & Official（6 repos）
- NousResearch/hermes-agent（237K ⭐）
- NousResearch/hermes-agent-self-evolution（5.1K ⭐）— DSPy + GEPA 自我優化
- NousResearch/autonovel（1.5K ⭐）— 10萬字小說生成
- NousResearch/hermes-paperclip-adapter（1.8K ⭐）— 企業管理系統整合
- NousResearch/Hermes-Function-Calling（1.4K ⭐）
- NousResearch/atropos（1.3K ⭐）— RL 訓練框架

#### Workspaces & GUIs（23 repos）
- nesquena/hermes-webui（17.6K ⭐）
- outsourc-e/hermes-workspace（6.5K ⭐）— 聊天/終端機/記憶瀏覽器
- fathah/hermes-desktop（14K ⭐）— 桌面伴侶
- farion1231/cc-switch（129K ⭐）— 跨平台 manager（Claude/Hermes/Codex 等）
- EKKOLearnAI/hermes-studio（10.5K ⭐）— 多平台 chat/排程/分析

#### Skills & Skill Registries（47 repos）
- mukul975/Anthropic-Cybersecurity-Skills（30.9K ⭐）— 754 資安 skills
- wondelai/skills（2K ⭐）— 62 skills + 12 guided journeys
- Agents365-ai/drawio-skill（7.9K ⭐）— draw.io 圖表生成
- conorbronsdon/avoid-ai-writing（3.2K ⭐）— 去除 AI 寫作風格
- mohitagw15856/pm-claude-skills（30K ⭐）— 822 專業 skills
- romanescu11/hermes-skill-factory（540 ⭐）— 自動生成 skills 的 meta-skill
- adnw-vinc/hermes-nextcloud（91 ⭐）— Nextcloud 檔案/日曆/筆記
- Shine8592/china-briefing（1.3K ⭐）— 多尺度中文資訊簡報
- ZeroPointRepo/youtube-skills（557 ⭐）— YouTube 字幕/頻道/播放清單
- black-forest-labs/skills（531 ⭐）— FLUX 圖像生成

#### Multi-Agent & Swarms（8 repos）
- zouroboros-swarm-executors
- 1ilkhamov/opencode-hermes-multiagent
- bigiron
- polybrain（Parallel 多模型協調）

#### Memory Providers（5 repos）
- honcho-self-hosted
- hindsight
- plur
- gbrain
- mnemosyne

#### Deployment（8 repos）
- nix-hermes-agent（NixOS 部署）
- hermes-agent-docker
- evey-setup

#### Integrations & Bridges（11 repos）
- AaronWong1999/hermesclaw（WeChat bridge）

---

## 方向2：社群討論（X/Reddit）❌ 部分失敗

- Exa 查詢失敗，無直接結果
- Star 增速可作為社群關注度的代理指標

---

## 安裝建議優先順序（已評估）

| 順序 | Skill | 成熟度 | Stars | 理由 |
|------|-------|--------|-------|------|
| 1 | RobinBeraud/hermes-skills（finance/fmp） | beta | 9 | 股票 dashboard 直接相關 |
| 2 | wondelai/skills | production | 2K | 生態系最大，工程技能補充 |
| 3 | hermes-skill-factory | beta | 540 | 自動化累積 workflow skills |
| — | winterliu6/hermes-skills | production | 1 | stars 太少，暂缓 |
