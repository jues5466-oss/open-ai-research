# Skills 待評估列表

## 2026-08 月熱門 Hermes Skills

---

## 1. wondelai/skills
• 成熟度: production
• GitHub: 2K ⭐ · 209 forks
• 說明：商業/行銷/UX/編碼框架技能庫，基於暢銷書方法論（Synergy、SMART、AARRR、RACE 等）。提供 62 個 skills + 12 個互動式導引流程（metaskills），例如 create-business、improve-code-quality、design-code-architecture。
• 對你有意義的：生動系最大、驗證最多，彌補 TDD、系統化偵錯、技術債管理等工程技能。
• 需要：無特殊依賴，Hermes Agent 相容 agentskills.io 標準
• 安裝：`hermes skills tap add wondelai/skills`

---

## 2. hermes-skills (winterliu6)
• 成熟度: production（但僅 1 ⭐，社群活躍度低）
• GitHub: 1 ⭐ · 0 forks
• 說明：中文內容工作室，含 content-studio（微博/公眾號/抖音腳本生成）、security-newsletter（每週資安情報郵件）、tech-ops-bot（企業微信/飛書 IT 維運，含 Zabbix 監控整合）。
• 對你有意義的：tech-ops-bot 的 Zabbix 整合可補充你現有 IT 維運監控能力。
• 需要：Zabbix 環境（可選）、企業微信或飛書帳號（可選）
• 備註：stars 極少，社群驗證不足，安全性未經廣泛測試，建議最後考慮

---

## 3. hermes-skills (RobinBeraud)
• 成熟度: beta
• GitHub: 9 ⭐ · 0 forks
• 說明：26 個涵蓋 7 大類的技能庫，包括 finance/fmp（即時股價、公司基本面、財務報表、股票篩選、加密/外匯）、web/firecrawl（網站爬取）、github（repo/issue/PR 管理）、productivity（Google Workspace、Notion、Airtable）、software-development（TDD、系統化偵錯）。
• 對你有意義的：finance/fmp 可直接對接你的股票 dashboard，查即時股價和公司基本面；firecrawl 強化爬蟲能力。
• 需要：FMP_API_KEY（免費方案可用 https://site.financialmodelingprep.com/）
• 安裝：`cp -r finance/fmp ~/.hermes/skills/finance/` + 設定 .env

---

## 4. hermes-skill-factory
• 成熟度: beta
• GitHub: 540 ⭐ · 71 forks
• 說明：元 skill，在你工作時自動觀測並提議將重複流程轉成可重用 skill。例如你重複設定 Python 環境→安裝依賴→跑測試，它會問你要不要把這個儲存成一個 skill，支援 /skill-factory propose 手動觸發。
• 對你有意義的：你正在建立各種工作流，裝了它可以自動化積累你自己生態系的 skills。
• 需要：Hermes Agent v2026.3+，用 bash install.sh 安裝（非 hermes skills tap）
• 安裝：`git clone` + `bash install.sh`

---

## 安裝建議優先順序

| 順序 | Skill | 理由 |
|------|-------|------|
| 1 | RobinBeraud/hermes-skills（finance/fmp） | 與你現有股票 dashboard 直接相關 |
| 2 | wondelai/skills | 生態系最大、驗證最多，工程技能補充 |
| 3 | hermes-skill-factory | 自動化累積你個人的 workflow skills |

---

## 尚未評估

- winterliu6/hermes-skills（建議最後再考慮，社群驗證不足）
