# 03｜Enterprise Governance

## 1. Human by Exception

- Low Risk：Agent Auto Execute
- Medium Risk：Agent Execute + Notify
- High Risk：Agent Recommend + Human Approve

## 2. Evidence First

Agent 所有 Root Cause、方案與結論都應可回溯到：

- 資料來源
- 時間戳
- 版本
- 計算方式
- 判斷規則

## 3. Verify Gate

任何對策在進入 A7 前必須通過 Verify Gate。

## 4. Versioning

VAC 以版本管理：

```text
v0.x = 實驗 / 未正式驗證
v1.x = 已驗證正式版
v2.x = 重大規格變更
```

## 5. Separation of Knowledge

公開 GitHub 只放：

- 通用框架
- 教學案例
- 匿名範本
- Schema

企業內部保存：

- 客戶資料
- 生產參數
- 品質事故
- 配方 / Know-how
- 商業機密
