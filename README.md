 # HR Attrition Analysis 👥

A data analysis project exploring employee attrition patterns 
using the IBM HR Analytics dataset.

---

## 📌 Project Objective
To analyze why employees leave the company and identify key 
factors driving attrition — helping HR teams make data-driven 
retention decisions.

---

## 📂 Project Structure
hr-attrition-analysis/

├── data/

│   ├── raw/                        # Original dataset

│   └── processed/                  # Cleaned dataset

├── notebooks/

│   ├── 01_data_exploration.ipynb   # Data cleaning

│   ├── 02_EDA_Visualization.ipynb  # Charts & analysis

│   └── 03_insights_summary.ipynb   # Key insights

├── dashboard/

│   ├── hr_attrition_dashboard.pbix # Power BI dashboard

│   └── dashboard_screenshot.png    # Dashboard preview

├── reports/                        # All chart images

├── requirements.txt

└── README.md

---

## 📊 Dataset
- *Source:* [IBM HR Analytics — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- *Records:* 1,470 employees
- *Features:* 35 columns
- *Target:* Attrition (Yes/No)

---

## 🛠️ Tools Used
- *Python 3.13* — Data analysis
- *Pandas & Numpy* — Data manipulation
- *Matplotlib & Seaborn* — Visualizations
- *Jupyter Notebook* — Development environment
- *Power BI Desktop* — Interactive dashboard

---

## 📈 Dashboard Preview
![HR Attrition Dashboard](dashboard/dashboard_screenshot.png)

---

## 🔍 Key Insights
1. *Overall attrition rate is 16.12%* — 237 out of 1,470 employees left
2. *Sales department* has the highest attrition at 20.6%
3. *Employees doing overtime* are 3x more likely to leave
4. *Young employees (18-25)* have the highest attrition at ~35%
5. *Low salary* is a major driver — employees who left earned $2,000 less on average
6. *Early tenure risk* — most exits happen within first 2 years

---

## 💡 Business Recommendations
1. Focus retention efforts on Sales department
2. Create career growth paths for young employees
3. Reduce or fairly compensate overtime
4. Review salary structure for low earners
5. Strengthen onboarding program for new joiners
6. Run engagement programs to boost job satisfaction

---

## 🚀 How to Run
1. Clone the repository:
git clone https://github.com/shirisha-seetha/hr-attrition-analysis.git

2. Install dependencies:
pip install -r requirements.txt

3. Download dataset from kaggle and place in:
data/raw/WA_Fn-UsaC_-HR-Employee-Attrition.csv

4. Run notebook in order:
01->02->03

5. open dashboard:
dashboard/hr_attrition_dashboard.pibx

---

## Author
** Shirisha Seetha **
--linkedIn:[https://www.linkedin.com/in/seetha-shirisha-268a81375]
--GitHub:[https://github.com/shirisha-seetha]
