# CMP 262: Data Exploration and Visualization with Python

## Objective

Use pandas to explore and clean a small student-interest dataset, then use Matplotlib to create charts that communicate what you discover.

This assignment introduces Matplotlib for the first time. You will practice one chart at a time and explain what each chart shows.

## Getting Started

1. Select **Use this template → Create a new repository**.
2. Choose your personal GitHub account as the owner.
3. Name your repository **LastName-FirstName-CMP262-Matplotlib**.
4. Set the repository to **Public** and select **Create repository**.
5. Clone your new repository to your computer.
6. Open the cloned repository in Visual Studio Code.
7. Open **MatplotlibAssignment.ipynb**.
8. Select a Python kernel and run the notebook from top to bottom.

**Important:** Work in your own repository, not the instructor's starter repository.

## What You Need to Do

### Part 1: Load and inspect the data

- Import pandas and Matplotlib.
- Read `data/student_interest_survey.csv` into a pandas DataFrame.
- Display the first rows, dimensions, column names, data types, and missing-value counts.

### Part 2: Clean the data

- Standardize the column names.
- Remove duplicate rows.
- Decide how to handle missing values.
- Standardize inconsistent values in at least one text column.
- Confirm that the cleaned data is ready for analysis.

### Part 3: Create charts

Create all five charts below:

1. A bar chart that compares categories.
2. A histogram that shows the distribution of a numeric column.
3. A scatter plot that compares two numeric columns.
4. A line chart that uses sorted numeric data.
5. A pie chart that shows parts of a whole.

Every chart must include a clear title. Add axis labels when they apply. Use readable colors and an appropriate figure size.

### Part 4: Explain your results

After every chart, add a Markdown cell with two or three sentences explaining:

- What the chart displays.
- What pattern or result you notice.
- Why that result may matter.

### Part 5: Save your work

- Save at least two charts as PNG files in the `charts` folder.
- Save the cleaned DataFrame as `cleaned-data/student_interest_survey_cleaned.csv`.
- Complete `AI-Use-Report.md`.
- Run all notebook cells and make sure no errors remain.

## Required Repository Files

- `MatplotlibAssignment.ipynb`
- `AI-Use-Report.md`
- `data/student_interest_survey.csv`
- `cleaned-data/student_interest_survey_cleaned.csv`
- At least two PNG chart files in `charts`

## Rubric: 100 Points

| Area | Points |
|---|---:|
| Load and explore the data | 15 |
| Clean the data | 20 |
| Five required charts | 35 |
| Titles, labels, colors, and readability | 10 |
| Written interpretation of charts | 10 |
| Saved CSV, saved charts, and organized repository | 5 |
| Completed AI Use Report | 5 |

## Submit Your Work

Use these commands after completing the assignment:

```bash
git status
git add .
git commit -m "Complete Matplotlib assignment"
git push
```

Open your repository on GitHub and confirm that your latest notebook, cleaned CSV, and chart images appear there. Submit the link to your public repository in Blackboard Ultra.

**Uploading work to GitHub alone does not count as submitting the assignment.**
