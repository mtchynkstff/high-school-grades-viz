# High School Semester Grades Visualization

**Goal:** Visualize pass/fail rates and grade distributions over time and subgroups to inform academic supports.

## Project Overview
- Cleaning & Mapping: Convert letter grades to pass/fail and numeric bins (document mappings).  
- Cohorts: Define expected grad year; show example formula and edge cases.  
- Visuals: Trends over semesters; subgroup comparisons with sample sizes and confidence intervals.  
- Output: Export tidy summary CSV for dashboards; optional Streamlit app for slicing.

## Pass/Fail Mapping (example)
| Letter | Pass? |
|---|---|
| A/B/C | 1 |
| D | 1 (configurable) |
| F | 0 |
| I/NG/WF | excluded or mapped per policy |

> Tip: Add sensitivity analysis showing how pass rates change if D is excluded.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Virtual-Academy-Grades-Clean.ipynb
```

## Structure
```
.
├── notebooks/Virtual-Academy-Grades-Clean.ipynb
├── data/  # raw/processed files
├── reports/figures/
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

_Last updated 2025-11-11._
