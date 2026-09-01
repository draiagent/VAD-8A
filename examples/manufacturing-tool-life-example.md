# Example｜刀具壽命監控問題

## A2 VAD Problem Card

- What：加工軸出現過多毛邊
- Where：Machining Line 2
- When：指定期間
- Detected by：客戶 / 品質檢查
- Defect Rate：4.5%
- Defective Parts：450 / month
- Scrap Cost：高額月報廢成本

## A3 Containment

- 100% inspection
- Inventory sorting
- Additional process checks
- Temporary tool replacement
- Operator alert

## A4 Root Cause Reasoning

```text
Why 1：刀具磨損
Why 2：未監控刀具壽命
Why 3：沒有換刀標準
Why 4：預防保養清單不完整
Why 5：缺乏維護控制系統
```

Root Cause Hypothesis：缺乏刀具壽命監控與維護控制機制。

## A5 Corrective Action

- 導入刀具壽命監控
- 建立預防保養週期
- 設定換刀提醒
- 更新作業指導書
- 訓練操作員

## A6 Verify

示意結果：

| KPI | Before | After |
|---|---:|---:|
| Defective Parts | 450 | 50 |
| Defect Rate | 4.5% | 0.5% |
| FPY | 95.5% | 99.5% |

Corrective Action Effectiveness ≈ 88.89%

## A7 Prevention & Automation

將以下內容轉成 verified VAC：

- Trigger：刀具壽命達門檻或缺陷率異常
- Agent：Monitoring Agent
- Rule：超過門檻 → Alert / 建議換刀 / 依風險決定是否需人工批准
- Verify：Defect Rate、FPY、Scrap Cost

## A8 Learn & Reuse

將成功規格保存於企業 VAC Library；下一次相似設備或製程異常，可直接調用並調整參數。
