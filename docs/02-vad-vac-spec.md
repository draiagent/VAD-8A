# 02｜VAD / VAC Specification

## VAD 最小規格

VAD Problem Card 建議至少包含：

- Problem Statement
- What / Where / When / Who / Why important / How many / How much
- Current KPI
- Target KPI
- Evidence / Data Source
- Process / System Boundary
- Human Owner
- Related Agent
- Risk Level
- Next Action

## VAC 最小規格

```yaml
name: string
version: string
trigger: object
input: object
context: object
agents: array
tools: array
rules: array
workflow: array
output: object
verify: object
exception: object
owner: string
status: draft|verified|deprecated
```

## 狀態治理

- `draft`：尚未完成驗證，不得自動大規模執行
- `verified`：已通過 A6 Verify，可進入 A7
- `deprecated`：已被更新版本取代或證實失效
