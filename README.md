# AI Academic Writing Survey Analysis

This repository contains a reusable Python analysis workflow for the AI use and academic writing survey collected from master’s students.

## Contents
- `notebooks/survey_analysis.ipynb` — full survey analysis notebook
- `data/` — folder for the survey CSV file

## Expected data file
Place your LimeSurvey export in:
- `data/results-survey563129.csv`

The notebook is designed for a LimeSurvey export with columns such as:
- `BFreq` — AI usage frequency
- `BTools[...]` — AI tools used
- `BUse[...]` — tasks performed with AI
- `BLiteracy[...]` — AI literacy statements
- `CConf[...]` — confidence in research tasks
- `DGSP1` ... `DGSP5` — good scientific practice items
- `EAtt[...]` — attitudes toward AI in academic work
- `FHardest` and `FCLARAExpect` — open-ended reflections

## Run the notebook
1. Open Jupyter Notebook or JupyterLab.
2. Launch the notebook: `notebooks/survey_analysis.ipynb`
3. Run all cells.

## Output
The notebook produces:
- descriptive statistics
- frequency tables
- tool and task usage summaries
- Likert-scale summaries
- charts and visualizations
- open-ended response summaries

This workflow is ready for both the pre-test and post-test dataset.
