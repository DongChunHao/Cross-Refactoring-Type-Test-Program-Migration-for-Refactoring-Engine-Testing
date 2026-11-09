| Directory | Contents | Paper stage |
|---|---|---|
| `AutoRefactor/` | Execution layer that invokes each IDE's refactoring API; runs the program before and after the transformation, then compiles and executes it | Steps 5–7 |
| `Dataset/` | Structured historical data exported per IDE (`goland.csv`, `Clion.xls`, `rider.xls`, `eb.xls`) | Steps 1–2 |
| `Historybugs/` | Archived original bug reports collected from GitHub / Bugzilla / YouTrack | Step 1 |
| `Prompt/` | Four prompt templates (extraction, compilation-error repair, cross-type migration, behavioural test generation) plus few-shot examples | Steps 2–4, 6 |
| `TestingCase/` | Migrated test programs together with their refactoring specifications (operation, target element, parameters) | Steps 4–5 |
| `index.html` | Project page listing the reported bugs | Step 7 |
