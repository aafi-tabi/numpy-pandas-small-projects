# NumPy & Pandas Small Projects

Four small projects that practice data cleaning and analysis with NumPy and Pandas, from handling missing values and merging tables to working with 3D arrays.

> **Note:** All data in these projects is sample data that I typed in or generated with a random seed, so the results are for practice, not real-world findings.

> **How this was built:** I wrote these scripts myself as practice. AI was used only for small fixes to a few of them and for writing this README.

## Projects

| Project | What it does | Skills practiced |
|---|---|---|
| [Developer Log Analysis](./developer-log-analysis/main.py) | Cleans developer profile and daily log tables, merges them, and summarizes coding, sleep and bug-fix activity per developer. | Missing values, duplicates, merging, groupby, rolling averages, binning |
| [Developer Productivity Tracker](./developer-productivity-tracker/main.py) | Another pass over developer data with profile cleanup, productivity categories and bugs-per-grade summaries. | Cleaning, merging, groupby and transform, categorizing |
| [Wellness AI Preprocessing](./wellness-ai-preprocessing/main.py) | Prepares a NumPy array of wellness data (4 users, 7 days, 5 measurements) with scoring, filtering and capping. | 3D arrays, boolean masks, views vs copies, iterating with nditer, aggregation |
| [Smart City Fitness Analytics](./smart-city-fitness-analytics/main.py) | Generates fitness data for 6 users over 10 days and finds averages, health scores and each user's best day. | Random data, array shapes, clipping, matrix operations, aggregation |

## Tech Stack

Python 3, NumPy, Pandas

## Getting Started

Install the libraries once:

```bash
pip install -r requirements.txt
```

Then run any project from inside its folder:

```bash
cd developer-log-analysis
python3 main.py
```

## What I Learned

- Cleaning messy tables: filling or dropping missing values and removing duplicates
- Combining tables and summarizing them by group
- Thinking in array shapes: users, days and features
- The difference between a copy and a view in NumPy, and why changing a view changes the original
- Filtering data with conditions instead of loops

## About

This repository documents my hands-on practice with NumPy and Pandas. Each script is a small, self-contained exercise in preparing data for analysis.

## License

This repository is licensed under the [MIT License](./LICENSE).
