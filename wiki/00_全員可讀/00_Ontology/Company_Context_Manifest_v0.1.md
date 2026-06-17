# Company Context Manifest — doT v0.1

> AI bootstrap 文件：任何接公司脈絡的 AI（Claude Project / NotebookLM / 校準器）先讀這份。
> 性質為「精簡、可機器讀的開機脈絡」，深層 schema 與治理機制不在此暴露。
> 來源：doT 公司雲腦（company scope）＋ Drive `boss_model.md` ＋ Molly 隱性知識訪談。
> 日期：2026-06-17 ｜ 版本：v0.1 DRAFT ｜ 維護：Bek
> 證據紀律：`[Observed]` / `[Inferred]` / `[Gap]`。**未經查證者一律標 `[Gap]`，不寫成結論。**

---

## 1. 公司識別（法人）

| 法人 | 統一編號 | 備註 |
|---|---|---|
| 聯合治作股份有限公司 | 42820677 | `[Observed]` |
| 構築室內裝修設計工程有限公司 | 45112655 | `[Observed]` 設計工程主體（SIIR 申請人） |
| 離線生活有限公司 | 90359653 | `[Observed]` 設立 2022-08-09，資本 NT$200萬，旅館業 J901020；通樑東案申請主體 |

對外整合品牌：**doT & Associates（構築設計・聯合治作）** ｜ 代表人：**林建華**。

> 開立發票/抬頭依「選取的專案」自動對應法人，填表人不需手動選（見代墊費用系統設計）。`[Observed]`

## 2. 核心業務與品牌線

| 品牌線 | 內容 | 狀態 |
|---|---|---|
| 治器 dotsuwa | 陶藝教室/器物選品/酒藏，官網 + 門市 | 營運中 `[Observed]` |
| HIDDEN KURA | 會員制/訂購制 酒×器 電商，與治器官網定價統一、結構差異化 | 籌備中（林總要求不得因人力延遲）`[Observed]` |
| doTerraform | 模組木構/微型建築設備底盤系統，發明專利 I798139 | SIIR 補助主軸 `[Observed]` |
| 通樑東離線生活旅居聚落 | 澎湖白沙鄉旅居開發案，申請主體=離線生活有限公司 | 計畫書送件前 `[Observed]` |
| 設計工程案 | 室內裝修/木構專案（如 Rootopia LA、各公設專案） | 營運中 `[Observed]` |

## 3. 目標客群（依品牌線不同）`[Inferred]`

中高端深度體驗客、企業 Off-site/B2B、台日文化交流、餐飲通路與高端贈禮、陶藝/品飲會員。
（各線精確 TA 與優先序 → `[Gap]`，待各業務主管補。）

## 4. 現階段重點目標（2026 Q2）

- HIDDEN KURA 網站上線（不得延遲）`[Observed]`
- 通樑東計畫書送件 + 送件後行動（JETRO、SROI、企業 Off-site）`[Observed]`
- 代墊費用填報系統改版（Claude API 判讀，進入實作）`[Observed]`
- 公司 AI 部署：Wiki / 老闆校準器 / 公司雲腦落地 `[Observed]`

## 5. 老闆決策標準（摘要 → 詳見主管限定）

判斷一律引用《Boss Decision Model》條目編號。摘要：`[Observed]`
- **紅線（直接擋/升級）**：違法、欺騙客戶/隱藏資訊、重複承諾未執行。
- **設計**：結構必須對齊功能；排斥「華麗但鬆散」。
- **客製**：採標準模組，客戶「選」不「改」；繞過系統的客製 → 擋。
- **報價/人際**：必留 buffer，寧可慢、不被客戶節奏推走。
- **對外**：不解釋、不辯論；內部系統優先。
- 完整模型：`01_主管限定/管理層治理/Boss_Decision_Model_林建華_v0.1`
- Yvon 版：`[Gap]` 待建。

## 6. AI 高風險動作（必須走校準器 + 升級，不可自動執行）

`[Observed/Inferred]`
- 對外報價、折扣、客製承諾
- 合約/MOU 文字、補助送件文字
- 客戶/夥伴正式回覆
- 涉及外部夥伴 / 投資人 / SIIR / A 輪
- **任何編造數據、來源、真品/來源證明 → 絕對禁止**

## 7. 核准資料來源 / 寫回規則

- 讀取：doT 公司雲腦（company scope）、公司 Shared Drive、各案資料夾、本 Wiki。
- 寫回公司雲腦：scope 預設 personal；公司知識需明確 company；回報主管用 report_up。
- session 總結**不可**直接寫進 Open Brain → 須過 Wiki Patch → Brain Candidate → Promotion Gate。`[Observed]`

## 8. 升級條件（Escalate）

- 踩任一紅線
- 客製超出標準模組 / 報價金額大且 buffer 不足
- 兩位總監（林建華 vs Yvon）標準衝突 → **一律升級，AI 不自行裁決**（Boss Model H.9）`[Observed]`
- 模型未覆蓋（標 Gap）

## 9. 已知 GAP（待補）

- Yvon 老闆決策模型
- 各品牌線精確 TA、各主管 RACI
- 5 條核心 SOP
- 多數員工角色卡（見 `06_團隊管理/GAP_待訪談清單`）
