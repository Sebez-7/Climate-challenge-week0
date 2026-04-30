# African Climate Trend Analysis (Week 0)

## Project Overview
This project focuses on the exploratory data analysis (EDA) of historical climate data (2015–2026) for five African nations: **Ethiopia, Kenya, Sudan, Tanzania, and Nigeria**. The objective is to provide evidence-backed insights to support Ethiopia’s position as the host for **COP32**.

## Business Objective
As a Junior Data Analyst at EthioClimate Analytics, I am identifying climate trends, seasonal patterns, and anomalies. My analysis follows the "Negotiation-Grade" ladder:
1. **What is changing?** (Trends & Baselines)
2. **What did it cause?** (Impact Statistics)
3. **What does it demand?** (Policy & Finance Asks)

## Tech Stack & Environment
- **Language:** Python 3.10+
- **Libraries:** Pandas, Numpy, Matplotlib, Seaborn, Scipy
- **CI/CD:** GitHub Actions (Automated dependency checks)
- **Version Control:** Git (Conventional Commits)

## Project Structure
├── .github/workflows/  # CI/CD pipelines
├── notebooks/          # Exploratory Data Analysis (EDA) notebooks
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation

## Setup Instructions
1. Clone the repository: `git clone https://github.com/Sebez-7/Climate-challenge-week0.git`
2. Create a virtual environment: `python -m venv venv`
3. Activate environment: `source venv/bin/activate` (or `venv\Scripts\activate` on Windows)
4. Install dependencies: `pip install -r requirements.txt`

## Key Findings (Interim)
- **Data Cleaning:** Handled NASA's -999 sentinel values and converted DOY/YEAR to standard datetime formats.
- **Trend Analysis:** Initial findings for Ethiopia show [Insert brief finding, e.g., a steady warming trend in T2M].# Climate-challenge-week0
