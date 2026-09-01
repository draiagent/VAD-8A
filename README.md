# VAD-8A

## AI to Agent Enterprise Problem Solving Framework

> **VAD-8A 建構的是「AI Coach 益力康陳董如何把傳統問題解決能力，變成 Agent 可執行、可驗證、可重用的企業能力」。**

**AI Coach 益力康陳董 | 2026 AI to Agent**

---

## 1. 專案定位

VAD-8A（Visual Agent Design – 8 Agent Disciplines）是一套面向企業 AI to Agent 時代的問題解決方法論。它保留傳統 8D Problem Solving 的核心紀律：定義問題、暫時圍堵、根因分析、永久改善、成效驗證、防止再發與知識沉澱；但將每一階段重構為 **可視覺化、可規格化、可交給 Agent 執行、可驗證、可版本化與可重用** 的企業能力。

VAD-8A 的目的，不是把 8D 換成 AI 名詞，而是把「一次性問題解決」轉成「企業能力資產」。

---

## 2. 一句話核心

> **VAD，讓問題被看見；VAC，讓任務被定義；Agent，讓流程被執行；Verify，讓結果被證明；Reuse，讓能力持續複利。**

另一個更直接的企業版表述：

> **不是讓 AI 幫企業多解一次問題，而是讓企業每解一次問題，就多累積一項 Agent 能力。**

---

## 3. 從 8D 到 VAD-8A

| VAD-8A | 傳統 8D 對應 | VAD-8A 新定義 | 主要產物 |
|---|---|---|---|
| **A1 Agent Formation** | D1 團隊組成 | 定義 Human Owner、Orchestrator 與專業 Agent 權責、權限與交接點 | Agent Role Map |
| **A2 Visual Problem Definition** | D2 定義問題 | 把資料轉成 5W2H、影響、成本、邊界的視覺問題卡 | VAD Problem Card |
| **A3 Containment Execution** | D3 暫時圍堵 | 依既有規則啟動止血措施，並依風險保留人工批准 | Containment VAC |
| **A4 Root Cause Reasoning** | D4 根因分析 | 以 5 Why、Fishbone、歷史案例形成可追蹤的根因假說與證據鏈 | Root Cause Map |
| **A5 Corrective Action Design** | D5 永久對策 | 產生與比較改善方案，評估成本、風險、時間與效益 | Action VAC |
| **A6 Verify** | D6 驗證成效 | Agent 自動比較 Before / After KPI，確認方案是否有效 | Verify Report |
| **A7 Prevention & Automation** | D7 預防再發 | 將有效方案轉成 SOP、Rule、Skill、Workflow 與監控機制 | Reusable Capability |
| **A8 Learn & Reuse** | D8 表揚與結案 | Lessons Learned、版本化、知識沉澱與再次調用 | Enterprise Memory |

---

## 4. VAD-8A 核心閉環

```text
異常 / 問題發生
      ↓
A1 Agent Formation
      ↓
A2 VAD Problem Card
      ↓
A3 Containment Execution
      ↓
A4 Root Cause Reasoning
      ↓
A5 Corrective Action Design
      ↓
A6 VERIFY
   ↙       ↘
無效         有效
 ↓            ↓
回 A4        A7 Prevention & Automation
               ↓
          A8 Learn & Reuse
               ↓
           VAC Library
               ↓
      下一次相似事件直接調用
```

---

## 5. VAD 與 VAC 的角色

### VAD — Visual Agent Design

VAD 的任務是讓人與 Agent **先看懂問題、角色、流程、證據與決策點**。

VAD 應至少呈現：

- 問題邊界與 5W2H
- 相關角色與 Agent 分工
- 資料來源與證據
- Root Cause 推理鏈
- Workflow 與交接點
- Before / After 指標
- 例外與人工介入點

> **VAD = See the Problem.**

### VAC — Visual Agent Capability

VAC 的任務是把已驗證的方法，固化成 Agent 可以重複執行的企業能力規格。

建議標準欄位：

```text
Trigger
Input
Context
Agent
Tools
Rules
Workflow
Output
Verify
Exception
Owner
Version
```

> **VAC = Execute the Capability.**

---

## 6. 企業治理原則

### 6.1 Human by Exception

VAD-8A 不是 Zero Human。應依風險分層：

| 風險 | 執行模式 |
|---|---|
| 低風險 | Agent 自動執行 |
| 中風險 | Agent 執行 + 通知 Human Owner |
| 高風險 | Agent 建議 + Human Approval |

例如：

- 自動標記異常：可自動
- 自動產生隔離清單：可自動
- 停線：依權限與制度
- 產品召回：需授權
- 重大客戶通知：通常需人工確認

### 6.2 Root Cause 必須是「可驗證假說」

AI 不直接宣布 Root Cause。正確流程是：

```text
Agent 提出 Root Cause Hypothesis
→ 證據比對
→ 現場 / 數據驗證
→ Verify
→ Root Cause Confirmed
```

### 6.3 沒有 Verify，不得固化進 VAC

錯的方法一旦被自動化，錯誤會被規模化。因此：

> **A5 找方法，A6 證明方法，A7 才安裝方法。**

---

## 7. Traditional → AI Native → AI to Agent

```text
Traditional
Human Executes
      ↓
AI Native
Human + AI
      ↓
AI to Agent
Human Designs
Agent Executes
System Verifies
Enterprise Reuses
```

### Traditional 8D
人依制度與會議紀律解決問題。

### AI Native 8D
人使用 AI 協助寫 5W2H、5 Why、報表與方案。

### VAD-8A
人設計問題解決規格；Agent 依規格執行；系統 Verify；成功方法進入 VAC 與企業能力庫持續重用。

---

## 8. 建議企業 KPI

### 問題解決 KPI
- Time to Detect
- Time to Contain
- Time to Root Cause
- Time to Correct
- Recurrence Rate
- Defect Rate
- FPY
- COPQ
- Customer Complaint Rate

### Agent 化 KPI
- Agent 自動處理率
- Human Exception Rate
- Verify Pass Rate
- VAC Reuse Rate
- 平均處理時間下降率
- 人工核對時間下降率
- 重複問題自動處理覆蓋率

---

## 9. Repo 結構

```text
VAD-8A/
├─ README.md
├─ LICENSE
├─ NOTICE.md
├─ CITATION.cff
├─ CONTRIBUTING.md
├─ SECURITY.md
├─ CHANGELOG.md
├─ docs/
│  ├─ 00-philosophy.md
│  ├─ 01-framework-overview.md
│  ├─ 02-vad-vac-spec.md
│  ├─ 03-governance.md
│  ├─ 04-a1-a8-playbook.md
│  ├─ 05-kpi-verify.md
│  └─ 06-enterprise-adoption.md
├─ templates/
│  ├─ VAD-Problem-Card.md
│  ├─ VAC-Capability-Card.md
│  ├─ Root-Cause-Map.md
│  ├─ Verify-Report.md
│  └─ Lessons-Learned.md
├─ examples/
│  └─ manufacturing-tool-life-example.md
└─ schemas/
   └─ vac-capability.schema.json
```

---

## 10. 品牌署名

所有公開教材、圖卡、簡報與延伸教學，建議使用：

> **AI Coach 益力康陳董 | 2026 AI to Agent**

推薦方法論標題：

> **VAD-8A｜8 Agent Disciplines**  
> **AI to Agent Enterprise Problem Solving Framework**

中文副標：

> **把傳統問題解決能力，變成 Agent 可執行、可驗證、可重用的企業能力。**

---

## 11. 版權與授權

Copyright © 2026 AI Coach 益力康陳董. All rights reserved for brand identity and trademarks.

本儲存庫程式碼、範本與文件依 MIT License 開放使用；但「AI Coach 益力康陳董」、「2026 AI to Agent」、VAD-8A 品牌識別、Logo 與人物肖像不因 MIT License 而授權為商標、品牌背書或冒充用途。詳見 `LICENSE` 與 `NOTICE.md`。

---

## 12. 最後總結

VAD-8A 的本質，不是把 8D 改名為 8A，而是完成三個企業級轉換：

1. **從文字討論 → 視覺化規格**
2. **從人工執行 → Agent 可執行流程**
3. **從一次性改善 → 可驗證、可重用的企業能力**

> **企業真正需要的，不是每次都重新問 AI，而是讓成功的方法被固化，讓 Agent 下次直接做對。**

**AI Coach 益力康陳董 | 2026 AI to Agent**
