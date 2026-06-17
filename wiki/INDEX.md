# doT 公司 Wiki — 索引（v0.1）

> Wiki = 原始素材壓縮成「可重複使用的營運脈絡」。這裡是 markdown 來源，
> 出版到公司 Shared Drive 後成為 Google Docs / 資料夾。
> 三層 = **資料夾結構**；真正的存取權限由 Drive 成員/資料夾分享設定控制（Bek 手動設）。

## 三層結構（依 2026-04-27 鎖定）

```
doT 公司 Wiki/
├── 00_全員可讀/
│   ├── 00_Ontology/
│   │   └── Company_Context_Manifest_v0.1        ← AI bootstrap，先讀這份
│   ├── 05_品牌內容/                              （治器 / HIDDEN KURA / doTerraform / 通樑東）
│   └── 06_團隊管理/
│       ├── role_card_TEMPLATE
│       ├── GAP_待訪談清單
│       └── SOP_TEMPLATE
├── 01_主管限定/
│   ├── 管理層治理/
│   │   ├── Boss_Decision_Model_林建華_v0.1
│   │   └── Boss_Decision_Model_Yvon_v0.1（GAP）
│   ├── 關鍵人員OS/
│   │   └── Key_Role_OS_Molly_v0.1
│   ├── 01_技術IP（設計主管）/
│   ├── 02_供應鏈（業務主管）/
│   ├── 03_客戶關係/
│   └── 04_財務法務（Hide + Yvon only）/
└── 02_案件交付區/                                （per-case 一個資料夾或獨立 Shared Drive）
```

## 存取分層原則

- **全員可讀**：營運脈絡、品牌內容、角色卡模板、SOP — 大家都該看到的共識層。
- **主管限定**：老闆決策模型（含員工判準，敏感）、關鍵人員 OS（隱性知識，源自 report_up）、技術 IP、財務法務。
- **案件交付區**：每案一夾；NotebookLM / Claude Project 各接固定子集 → 天然 role-based AI。

## v0.1 已建 / 待補

| 文件 | 狀態 | 來源 |
|---|---|---|
| Company Context Manifest | 🟡 v0.1 draft（含 GAP） | 公司雲腦 + boss_model.md + Molly 訪談 |
| Boss Decision Model — 林建華 | ✅ 完整 | Drive `boss_model.md` 鏡像 |
| Boss Decision Model — Yvon | ⬜ GAP（待訪談/匯入） | — |
| Key Role OS — Molly | ✅ v0.1 | Molly 隱性知識訪談報告 |
| Key Role OS — 育如 | ⬜ 已訪談（5/4），檔案待匯入 | — |
| 其他角色卡 | ⬜ 待訪談 | 見 GAP_待訪談清單 |
| 核心 SOP（5 條） | ⬜ 待補 | — |
