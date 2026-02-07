# Work-from-Home Burnout (Lab Submission)

## Dataset summary
This dataset contains **1,800 rows** (daily records) and **11 columns** about work-from-home behavior and outcomes.
Each row represents a day for a user (`user_id`) and includes:

- **Inputs (features):** `day_type` (Weekday/Weekend), `work_hours`, `screen_time_hours`, `meetings_count`, `breaks_taken`,
  `after_hours_work` (0/1), `sleep_hours`, `task_completion_rate`
- **Outcomes (labels):** `burnout_score` (continuous) and `burnout_risk` (categorical)

`burnout_risk` has 3 classes with strong imbalance:
- Low: 1,527
- Medium: 253
- High: 20

## Machine learning problem
**Goal:** Build a supervised model that predicts **burnout risk** (`Low`, `Medium`, `High`) from the work/sleep/productivity features.
This is a **multiclass classification** problem. A secondary option is **regression** to predict `burnout_score`.

**Why it matters:** Early prediction of burnout risk can help organizations or individuals adjust workload, meeting load,
break habits, and after-hours work to improve wellbeing.

## Repo contents (required)
- `README.md` (this summary)
- `notebooks/01_dataset_overview.ipynb` (loads the dataset and displays basic information)
- `assets/methodology_diagram.png` and `assets/methodology_diagram.pdf` (methodology diagram)

Generated on: 2026-02-07
