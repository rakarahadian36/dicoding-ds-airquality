
---

# 🌍 Air Quality Analysis Project: Wanshouxigong Station

## 📊 Project Overview
This project, submitted for the **"Learn Data Analysis with Python"** course from **Dicoding**, focuses on analyzing air quality data, particularly PM2.5 levels, from the Wanshouxigong station. The objective is to uncover trends, seasonal variations, and the impact of different weather conditions on air quality.

## 📚 Course Submission
This analysis serves as a course submission for **"Learn Data Analysis with Python"** offered by Dicoding. It showcases the application of data analysis techniques and visualization skills acquired throughout the course.

## 📑 Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Libraries Used](#libraries-used)
- [Key Insights](#key-insights)
- [How to Run the Dashboard](#how-to-run-the-dashboard)
- [About Me](#about-me)

## 📖 Introduction
The goal of this project is to analyze air quality data, specifically PM2.5 pollutant levels, and understand their relationship with various environmental factors. The analysis includes identifying trends, seasonal patterns, and correlations with weather conditions.

## 📈 Data Source
The dataset used in this project includes air quality measurements from the **Wanshouxigong station**, focusing on PM2.5 levels and related environmental data.

## 📦 Libraries Used
- **Streamlit**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **NumPy**
- **SciPy**
- **Statsmodels**

## 🔍 Key Insights
- **Seasonal Variation**: PM2.5 levels exhibit higher concentrations during colder months.
- **Weather Correlation**: Notable correlation between PM2.5 levels and weather conditions like temperature and humidity.
- **Trends & Patterns**: Insights revealed through comprehensive time series analysis.

## 🛠️ How to Run the Dashboard

To run the **Air Quality Analysis Dashboard**, follow these steps:

### 1. Setup Environment

**Create and Activate a Python Environment**:
- Using **Conda** (ensure [Conda](https://docs.conda.io/en/latest/) is installed):
  ```bash
  conda create --name airquality-ds python=3.9
  conda activate airquality-ds
  ```
- Using **venv** (standard Python environment tool):
  ```bash
  python -m venv airquality-ds
  source airquality-ds/bin/activate  # On Windows use `airquality-ds\Scripts\activate`
  ```

### 2. Install Required Packages
The following packages are necessary for running the analysis and the dashboard:
```bash
pip install pandas numpy scipy matplotlib seaborn streamlit statsmodels
```
Alternatively, you can install from a requirements file:
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App
1. **Navigate to the Project Directory** where `dashboard.py` is located.
2. **Run the Streamlit App**:
    ```bash
    streamlit run dashboard.py
    ```

### 📁 Additional Files
- The dataset used for this analysis is included in the project repository.
- A detailed Python notebook (`ds_airquality.ipynb`) containing the data analysis and visualizations is also provided.

---

### ⚠️ P.S.
Dicoding recommended creating well-organized folder structures, with `dashboard.py` in a dedicated `dashboard` folder. Therefore, the deployment for the Streamlit App reflects this setup, including the `requirements.txt` in the `dashboard` folder.

---

## 👤 About Me
- **Name**: Raka Rahadian
- **Email Address**: [rakarahadian36@gmail.com](mailto:rakarahadian36@gmail.com)
- **Dicoding ID**: [rakarahadian36](https://www.dicoding.com/users/rakarahadian36/)

--- 
