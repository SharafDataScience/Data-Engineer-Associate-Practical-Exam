# 🏋️‍♂️ Data Engineer Associate Exam - Virtual Reality Fitness

This Jupyter Notebook is a project or assessment related to a **Data Engineering Associate Exam**, focused on analyzing user data in a **Virtual Reality Fitness** setting.

## Project Overview

The notebook performs data cleaning and querying using SQL-style transformations, likely powered by a PostgreSQL backend or an embedded SQL environment. The dataset involves user information such as:

- `user_id`, `age`, `registration_date`
- `email`, `workout_frequency`

### Goals

- Clean null or inconsistent user data.
- Normalize fields like `workout_frequency`.
- Generate insights from game activity data.

##  Features

- Imputation for missing values (e.g., average age, default registration dates).
- Use of `COALESCE` and `CASE` logic for robust data preparation.
- Modular SQL queries for layered analysis.

## Technologies Used

- **Jupyter Notebook**
- **SQL** (likely PostgreSQL or SQL-compatible backend)
- **Pandas** (if used in other parts of the notebook)
- **Data Engineering concepts**: cleaning, joins, aggregations

## File Structure

```
Games.ipynb     # Main notebook containing the SQL and data analysis
README.md       # You're reading it!
```

## How to Run

1. Open `Games.ipynb` in Jupyter Lab or Jupyter Notebook.
2. Make sure any required SQL backend or environment is connected.
3. Run all cells in order to reproduce the analysis.


