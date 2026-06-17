# dotawork — doT 公司 AI 部署運維

這個 repo 是 doT（聯合治作 / 構築設計 / doT & Associates）AI 部署的**運維與內容來源**。
所有可 review、需留底的東西先寫在這裡（git 留版本），再「出版」到對應的落地位置
（Google Shared Drive、Supabase、Claude Code skill）。

> 環境提醒：本 repo 在遠端 ephemeral 容器內，所有成果以 commit + push 到指定分支為準。

## 目錄

```
wiki/        公司 Wiki 內容（markdown 來源 → 出版到公司 Shared Drive 成 Google Docs）
tracking/    Boss Calibrator 使用追蹤 + 用量 / personal-brain 計數 Dashboard（migration SQL / edge function / 前端）— 規格與代碼，待你在 Supabase 上線
```

## 三條部署線狀態（2026-06-17）

| 線 | 內容 | 狀態 |
|---|---|---|
| 公司 Wiki | 三層結構 + Company Context Manifest + 老闆決策模型 + 關鍵人員 OS | 🟡 repo 內容建置中；Drive 出版位置待定 |
| 使用追蹤 | 每位員工用校準器幾次 + 評分，server 端記錄 | ⬜ 規格 + 代碼待寫（本環境無 Supabase 憑證，只能產代碼供上線） |
| 用量 Dashboard | Supabase 用量/儲值預警 + 每人 personal brain 筆數（只看數量不看內容） | ⬜ 同上 |

## 既有基礎設施（參考，不在本 repo）

- 公司雲腦 MCP：Supabase project `psblglyzkaaumfegugxb`，connector 名「doT 公司雲腦」
- Boss Calibrator：Claude Code skill `boss-calibrator-a`，目前以 Google Drive + install.bat 分發（**本機 skill，無 server 端使用記錄 → 這是 tracking 線要補的洞**）
- 公司 Shared Drive「雲端硬碟」`0AKGYv69y10j2Uk9PVA`（目前僅含 boss-calibrator-a）

## 命名與證據紀律

Wiki 全文沿用證據標籤，禁止把推論寫成結論：
`[Observed]` 親口/親寫 · `[Inferred]` 多案推導 · `[Hypothesis]` 單一訊號待驗 · `[Gap]` 缺料，遇到一律升級。
