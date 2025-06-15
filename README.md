# Global AI Job Market & Salary Trends 2025 – Exploratory Data Analysis

This project presents a detailed exploratory data analysis (EDA) of the global AI and machine learning job market for the year 2025. By analyzing over 15,000 job listings across 50+ countries, it uncovers salary trends, hiring patterns, and key factors affecting compensation in the AI industry.

---

## Dataset Overview

- **Title**: Global AI Job Market & Salary Trends 2025
- **Source**: https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025/data
- **Records**: 15,000+ job listings
- **Features include**:
  - Salaries (normalized to USD)
  - Experience Levels (Entry, Mid, Senior, Executive)
  - Company Size (Small, Medium, Large)
  - Remote Work Ratios (0%, 50%, 100%)
  - Location, Industry, and Education Requirements
  - Benefits Score, Job Description Length
  - Time-based Posting Data
  - In-demand Skills & Keywords

---

## Project Objectives

- Analyze salary distributions across roles, regions, experience levels, and remote work statuses.
- Identify patterns and correlations between features (e.g., salary vs. benefits score, education, job description length).
- Visualize geographic trends and remote work influence on compensation.
- Explore industry-wise salary differences and company-level hiring behavior.
- Generate insights that are valuable for job seekers, recruiters, and market analysts.

---

## Analysis Conducted

### Univariate Analysis
- Distribution of salaries
- Frequency of experience levels and education requirements
- Company size and remote work prevalence

### Bivariate & Multivariate Analysis
- Salary vs Experience Level
- Salary vs Company Size
- Salary vs Remote Ratio
- Salary vs Education Level
- Salary vs Benefits Score
- Correlation Heatmap (Numerical Features)
- Scatterplots & Boxplots to explore outliers and relationships

### Hypothesis-Driven Exploration
- Do companies with higher benefits scores offer better pay?
- Are PhD holders consistently earning more?
- Does job description length correlate with higher compensation?
- Are larger companies offering more lucrative roles?

---

## Visualizations Used

- Histograms
- Boxplots
- Barplots & Countplots
- Scatterplots with regression lines
- Correlation Heatmaps
- Time series line charts

---

## Tools & Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy
- Seaborn, Matplotlib

---

## How to Run the Project

```bash
# Clone the repository
git clone https://github.com/Prishatank0607/Global_AI_Job_Market_Trends_EDA_2025.git

# Navigate to the project folder
cd Global_AI_Job_Market_Trends_EDA_2025

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate        # macOS/Linux
# venv\Scripts\activate         # Windows

# Install required packages
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
Open the Global_AI_Job_Market_EDA_2025.ipynb notebook to explore the complete analysis.
