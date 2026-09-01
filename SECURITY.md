# Security & Governance

VAD-8A 是企業問題解決方法論與參考規格，不應直接視為生產環境安全保證。

## 建議控制

- Agent 最小權限原則
- 高風險動作 Human Approval
- 資料來源可追溯
- Prompt / VAC / Workflow 版本化
- 操作紀錄與 Audit Log
- 敏感資料遮罩
- 企業機密不得進入公開模型或公開 Repo
- Verify 失敗時自動停止或降級

## 安全事件

若發現範本或 Schema 可能導致越權、自動化錯誤或資料外洩，請以私有管道回報維護者，不要在公開 issue 中張貼敏感細節。
