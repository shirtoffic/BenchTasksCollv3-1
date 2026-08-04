# Final Pool Tasks

Updated: 2026-08-04 (UTC) by the task-tracker agent.

## Task Requirements (from tasks/examples)

A task is considered **implemented** when it satisfies the requirements documented in `tasks/examples`:
1. `docs/task.md` - Non-empty and all English (no Chinese).
2. `docs/agent_system_prompt.md` - Non-empty and all English (no Chinese).
3. `docs/user_system_prompt.md` - Optional; must be all English if present.
4. `evaluation/main.py` - Must exist (evaluation script).
5. Other example files (`groundtruth_workspace/readme.txt`, `initial_workspace/readme.txt`, `preprocess/main.py`, `readme.txt`, `task_config.json`) - Only existence is checked.

## Current Final Pool (23 tasks, all implemented)

| Implementor | Implemented Tasks |
|---|---|
| fan-dev | loyalty-program, discount-calculator |
| gyy | tag-manager, sitemap-generator, robots-handler |
| haoze | media-organizer, streaming-service |
| jl_dev | customer-feedback-processor, inventory-management |
| junteng_dev | help-desk |
| junxian_dev | social-connector |
| lueyang-dev | territory-manager |
| lv | survey-builder, analytics-dashboard |
| ruige | web-crawler, log-analyzer |
| wenshuo-dev | cache-optimizer, scheduler |
| xiaochen_dev | status-checker, health-monitor |
| yuxuan-dev | sync-service |
| zhaochen | certificate-manager, storage-manager |

## Tasks still implementing (not in this pool)

- currency-converter (junxian_dev) - docs/task.md contains Chinese
- insights-engine (lv) - docs/agent_system_prompt.md contains Chinese
- audit-logger (yuzhen-dev) - docs/agent_system_prompt.md contains Chinese
- resource-monitor (yuzhen-dev) - docs/agent_system_prompt.md contains Chinese
- customer-portal (junteng_dev) - no evaluation/main.py, missing initial_workspace
- client-portal (lueyang-dev) - no task files exist on the branch tip

Statuses are tracked on the Notion page `Task Tracker` (page 3b262592-bca0-813e-8434-ebe284fb1075).
