# TaskNet

Interactive dashboard for *TaskNet: Building Occupational Task Inventories from Worker Interviews at Scale* (Wang, Haupt, Robinson, Lewis, Brynjolfsson, Yang).

- `index.html`: the dashboard
- `explorer.html`: the task Venn explorer, embedded in the dashboard
- `tasknet-data.csv`: the 202 TaskNet statements and 118 O*NET 31.0 tasks, one row each. `region` is new / overlap / missing; `refines`, `refined_by` and `overlaps` list the linked task IDs. O*NET tasks carry only the relevance, importance and frequency O*NET publishes.
