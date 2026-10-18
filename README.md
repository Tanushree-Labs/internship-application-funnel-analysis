# Internship Application Funnel Analysis

## Project Overview

The **Internship Application Funnel Analysis** project explores internship application outcomes using Python, Pandas, and data visualization. It analyzes application stages, conversion rates, rejection patterns, and response times to better understand where applicants experience the greatest drop-offs.

The project also uses rule-based Python logic to generate simple, data-driven recommendations based on the analysis.

## Objectives

- Analyze the distribution of applications across different stages.
- Calculate conversion rates between consecutive application stages.
- Identify the stages with the highest applicant drop-offs.
- Compare application outcomes across job roles, company types, and skill levels.
- Examine application response times.
- Generate practical recommendations based on observed patterns.
- Identify when sample sizes are too small to support reliable conclusions.

## Dataset

The project uses a synthetic dataset of 200 internship applications.

The dataset includes the following columns:

| Column | Description |
|---|---|
| `Application_ID` | Unique identifier for each application |
| `Role` | Job role applied for |
| `Company_Type` | Category of company |
| `Skill_Level` | Applicant's recorded skill level |
| `Stage` | Final application status |
| `Response_Time` | Recorded response time |
| `Last_Stage_Reached` | Furthest application stage reached |

**Note:** The dataset is synthetic and intended for educational and analytical purposes. Its results should not be treated as representative of real recruitment outcomes.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Git and GitHub

## Analysis Performed

- Application status distribution
- Stage-wise funnel conversion analysis
- Applicant drop-off analysis
- Role-wise outcome comparisons
- Company-type comparisons
- Skill-level outcome comparisons
- Response-time analysis
- Rule-based recommendations

## Project Structure

```text
internship_applications/
├── data/
│   └── internship_applications.csv
├── notebooks/
│   └── internship_application_funnel_analysis.ipynb
├── .gitignore
├── CONTRIBUTIONS.md
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Open a terminal in the project directory.
4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Open the notebook in VS Code with the Jupyter extension installed.
6. Run the notebook cells from top to bottom.

Make sure the dataset is located in the `data/` directory and the notebook is located in the `notebooks/` directory.

## Limitations

- The dataset is synthetic and does not represent real hiring data.
- The analysis describes observed patterns rather than predicting whether an applicant will be selected.
- Comparisons between groups may be affected by sample size and the distribution of applications.
- Rule-based recommendations are exploratory and should not be interpreted as guaranteed outcomes.

## Learning Outcomes

This project demonstrates practical skills in data cleaning, exploratory data analysis, Pandas operations, data visualization, funnel metrics, and basic rule-based recommendation logic.
