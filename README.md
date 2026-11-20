# 🇮🇳 India Tech Job Market & Hiring Intelligence — 2026

## 📌 Project Overview

This project focuses on analyzing India's technology job market using Exploratory Data Analysis (EDA) with Python.

The objective is to understand hiring patterns, identify high-demand technology roles, explore company hiring activity, analyze experience requirements, and discover geographical hiring trends.

The analysis aims to generate meaningful business insights that can help job seekers understand market demand and support workforce-planning decisions.

## 🎯 Business Objectives

- Identify the most frequently advertised technology roles.
- Analyze company-wise job posting volumes.
- Understand experience requirements across different roles.
- Identify major technology hiring locations in India.
- Analyze the relationship between job roles and locations.
- Explore work-mode preferences across job categories.
- Understand company role diversity and hiring specialization.

## 📊 Dataset Overview

The dataset contains **23,201 technology job postings** and **10 attributes**.

| Attribute | Description |
|---|---|
| job_id | Unique job posting identifier |
| job_title | Advertised job title |
| company_name | Hiring company |
| company_rating | Company rating |
| location | Job location |
| scraped_city | City associated with the posting |
| role_category | Classified job role |
| experience_raw | Original experience requirement |
| experience_min_yrs | Minimum required experience |
| experience_max_yrs | Maximum required experience |

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Understanding
Explored the dataset structure, dimensions, column names, data types and descriptive statistics.

### 2. Data Quality Audit
Performed data quality checks to understand the completeness and consistency of the dataset.

The notebook includes:
- Missing value analysis
- Duplicate record analysis
- Job ID uniqueness checks
- Data type validation
- Role classification quality
- Experience data quality
- Location standardization
- Job title standardization

### 3. Exploratory Data Analysis

Performed analysis across multiple business dimensions:

**Role Distribution:** Examined the distribution of technology job categories.

**Company Hiring Analysis:** Compared job posting volumes across companies.

**Experience Analysis:** Explored minimum and maximum experience requirements.

**Geographic Analysis:** Investigated hiring patterns across different locations.

**Role vs Location:** Analyzed how job opportunities vary by role and geography.

**Company vs Role:** Examined the types of roles advertised by different companies.

**Work Mode Analysis:** Explored work arrangements across job postings.

**Hiring Specialization:** Studied company role diversity and hiring volume versus specialization.

## 💡 Business Value

This analysis helps translate raw job posting data into meaningful information about India's technology employment landscape.

It can help job seekers understand role demand, experience expectations and hiring locations while providing a structured view of company recruitment patterns.

## 📚 Key Learnings

- Practical data analysis using Pandas.
- Data quality assessment and cleaning.
- Handling categorical and numerical variables.
- Exploratory Data Analysis.
- Data visualization and interpretation.
- Converting analytical findings into business insights.
- Developing a business-oriented analytical approach.

## ⚠️ Data Limitations

The findings are based on the job postings available in the analyzed dataset. They should not be interpreted as a complete representation of every technology job opportunity in India.

Job postings may change over time, and the analysis reflects the dataset used in this project.

## 📂 Project Structure

```text
India-Tech-Job-Market-Analytics/
│
├── EDA_Project.ipynb
├── README.md
└── .gitignore
```

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/Husanpreet0/India-Tech-Job-Market-Analytics.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open `EDA_Project.ipynb` and execute the cells.

Note: The original dataset must also be available locally, and the notebook's CSV file path should be updated accordingly.

## 👩‍💻 Author

**Husanpreet Kaur**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

[GitHub Profile](https://github.com/Husanpreet0)

---

⭐ If you find this project interesting, feel free to explore the notebook!
