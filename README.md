# 📊 AI Jobs Data Analysis

## 📌 Overview
This project analyzes a dataset of AI-related job listings to uncover key factors that influence salaries, job distribution, and hiring trends across industries, countries, and experience levels.

The goal is to identify **what drives compensation in AI jobs** and provide actionable insights using data analysis and visualization techniques.

---

## 📂 Dataset Information
- **File:** `ai_jobs.csv`
- **Rows:** 50,000  
- **Columns:** 14  
- **Key Features:**
  - `job_title`
  - `salary_min_usd`, `salary_max_usd`
  - `experience_level`
  - `industry`
  - `country`
  - `remote_type`
  - Other job-related attributes

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Checked structure, shape, and data types

### 2. Data Cleaning
- Verified missing values (none found)
- Handled any inconsistencies if present

### 3. Feature Engineering
- Created a new column:
  ```python
  Average Salary = (salary_min_usd + salary_max_usd) / 2
  ```

## 🔍 4. Exploratory Data Analysis (EDA)

Performed analysis using:

- Value counts for categorical variables

- **Pie charts for:**
  - Job titles
  - Countries
  - Remote work types

- **Bar plots for:**
  - Experience level vs salary
  - Remote type vs salary
  - Country vs salary

- Box plots for salary distribution

- Correlation heatmap for numeric features

---

## 📊 Key Insights

- 💼 **Experience Matters Most:**  
  Salary increases significantly with experience level.

- 🌍 **Geographical Impact:**  
  Salaries vary widely across countries.

- 🏠 **Remote Work Trends:**  
  Remote and hybrid roles show different salary distributions.

- 📈 **Salary Range:**  
  Most salaries fall between **$50,000 and $200,000+**

- 🧠 **Average Experience Required:**  
  Around **2 years** for many AI roles.

---

## 🧪 Hypothesis Testing

The project includes hypothesis formulation to validate:

- Whether experience level significantly impacts salary  
- The effect of remote work on compensation  
- Country-based salary differences  

---

## 📌 Visualizations

The notebook includes:

- Pie charts 📊  
- Count plots 📉  
- Bar graphs 📈  
- Box plots 📦  
- Heatmaps 🔥  

These help in understanding distributions, comparisons, and relationships between variables.

---

## 🚀 How to Run

### 1. Clone the repository

```
git clone https://github.com/Dev1822/AI-Jobs-EDA
cd AI-Jobs-EDA
```

### 2. Install dependencies

```
pip install pandas matplotlib seaborn
```

### 3. Run the notebook

---

Made By : https://github.com/Dev1822
