# HEARTBEAT.md

**🎯 ACTIVE PROJECT:** Invoice Agent MVP
**📁 Repository:** `~/scm/invoice_agent/`

## ⏱️ LAST HEARTBEAT
<!-- Update this timestamp every heartbeat run -->
**Last Run:** Fri 2026-02-13 23:51 GMT+1

## 🔇 QUIET HOURS
**00:00 - 08:00 (CET/CEST):** 
- Reply with **ONLY STRICLY** WITH "HEARTBEAT_OK" instead of progress reports, nothing More (you can still work silently)!
- Resume normal reporting after 08:00

## 🚀 HEARTBEAT SEQUENCE
Check for Open TASKS.md in the current Phase and delegate them (if not already in progress!). Make sure that you only do that if currently no task is running and we actively work on a Phase!
### Task workflow !IMPORTANT!:
** DON'T START PARALLEL TASKS ONLY ONE ALLOWED AT A TIME **
**Every new Phase start creates a branch** -> your job
**The next Task is selected and marked as 'InProgress' in the table in TASKS.md** -> your job
**The Task is delegated to spawned coding agents** -> sessions_spawn
**After the last Task in the Phase, there follows a Create PR Task** -> sessions_spawn
**After the PR creation there follows a PR review** -> sessions_spawn
**After PR review the fixing starts iteratively until all tests are fixed in the Github Actions CI pipeline** -> sessions_spawn
**The Definition of Done is a open PR with a green CI pipeline** -> your job
**You never merge a PR! The human does that** -> human

Report to the human:
```

HEARTBEAT REPORT - [TIMESTAMP]
⏱️ Since Last Heartbeat: [X minutes/hours ago]
✅ Task InProgress: [Task Number & short description from $Repository/TASKS.md]

💰 MODEL USAGE:
[Run 'codexbar --source cli --provider all' wait for completion it taks a bit and include results]

```