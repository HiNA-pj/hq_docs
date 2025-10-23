---
dept: kanrimon|wakemon|sabamon|machimon|kachimon
cycle_id: MAC-YYYYMMDD-XXX
risk_score: 0.34
human_ack: pending
affected_paths:
  - mon_standard/docs/<dept>/...
diff_stats:
  files_changed: 0
  lines_added: 0
  lines_removed: 0
test_evidence:
  - "lint: passed"
  - "schema-validate: passed"
window_gate: "22:00-06:00 JST"
safe_dirs: true
max_diff_guard: true
---
### Summary
- 変更概要と目的

### Detail
- 実施内容 / 注意点

### Checklist
- [ ] SAFE_DIRS内のみ変更  
- [ ] 差分上限内  
- [ ] レビュー担当者指定済（@reviewer）
