# 05｜KPI & Verify

## 品質類 KPI

- Defect Rate = Defects / Total Production × 100
- FPY = Good Units / Total Units × 100
- Containment Efficiency = Captured Defects / Total Defects × 100
- Corrective Action Effectiveness = (Before Defects - After Defects) / Before Defects × 100
- COPQ = Scrap + Rework + Warranty + Inspection + Complaint-related Cost

## Agent 化 KPI

- Auto Execution Rate
- Human Exception Rate
- Verify Pass Rate
- VAC Reuse Rate
- Mean Time to Detect
- Mean Time to Contain
- Mean Time to Verify
- Recurrence Rate

## Verify Gate 建議

```text
IF KPI improvement >= target
AND no critical side-effect
AND recurrence risk <= threshold
THEN status = verified
ELSE return to A4/A5
```
