# Internship Application Funnel Analysis

## Project Overview

The **Internship Application Funnel Analysis** project explores internship application outcomes using Python and data visualization. It uses Pandas to analyze application stages, outcome distributions, response times, and differences across job roles, company types, and skill levels.

The project also implements a simple rule-based recommendation system that generates suggestions based on patterns observed in the dataset.

## Objectives

- Analyze the distribution of applications across different stages.
- Examine funnel conversion rates and applicant drop-offs.
- Compare outcomes across job roles, company types, and skill levels.
- Investigate application response times.
- Generate rule-based recommendations from observed patterns.
- Consider sample sizes when interpreting results.

## Dataset

The project uses a **synthetic internship application dataset** stored in `data/internship_applications.csv`.

| Column | Description |
|---|---|
| `Application_ID` | Unique application identifier |
| `Role` | Job role applied for |
| `Company_Type` | Category of company |
| `Skill_Level` | Recorded skill level |
| `Stage` | Application status recorded in the dataset |
| `Response_Time` | Recorded application response time |
| `Last_Stage_Reached` | Furthest stage reached in the application process |

The dataset is intended for educational and analytical purposes. Its patterns should not be interpreted as representative of real recruitment outcomes.

## Tools and Technologies

- **Python** — analysis and logic
- **Pandas** — data manipulation and analysis
- **Matplotlib and Seaborn** — data visualization
- **Jupyter Notebook** — interactive analysis
- **Git and GitHub** — version control and project hosting

## Analysis Performed

- Application outcome distribution
- Funnel conversion and drop-off analysis
- Comparisons by job role, company type, and skill level
- Response-time analysis
- Rule-based recommendations
- Consideration of sample sizes and analytical limitations

## Project Structure

```text
internship-application-funnel-analysis/
├── data/
│   └── internship_applications.csv
├── notebook/
│   └── Internship_Application_Funnel_Analysis.ipynb
├── .gitignore
├── CONTRIBUTIONS.md
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Clone or download the repository.
2. Install Python and open a terminal in the project directory.
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `notebook/Internship_Application_Funnel_Analysis.ipynb` in VS Code with the Jupyter extension or in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

Ensure that the CSV file remains in the `data/` directory so that the notebook can locate it.

## Limitations

- The dataset is synthetic and does not represent real hiring outcomes.
- The analysis identifies patterns but does not predict an applicant's selection outcome.
- Group comparisons may be affected by sample sizes and uneven distributions.
- Rule-based recommendations are exploratory and are not guaranteed to improve application outcomes.

## Learning Outcomes

This project demonstrates practical skills in data cleaning, exploratory data analysis, Pandas, data visualization, funnel metrics, and basic rule-based recommendation logic.
