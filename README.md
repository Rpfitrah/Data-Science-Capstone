# 🚀 Data Science Capstone: Falcon 9 Landing Prediction & Analysis

![Repo Size](https://img.shields.io/github/repo-size/Rpfitrah/Data-Science-Capstone)
![Last Commit](https://img.shields.io/github/last-commit/Rpfitrah/Data-Science-Capstone)
![GitHub License](https://img.shields.io/github/license/Rpfitrah/Data-Science-Capstone)
![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Plotly Dash](https://img.shields.io/badge/Plotly-Dash-blueviolet)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

# 🚀 Data Science Capstone: Falcon 9 Landing Prediction & Analysis

*End-to-End Data Pipeline for Predicting Falcon 9 Booster Landing Success*

This capstone project is part of the **IBM Data Science Professional Certificate** program.  
It demonstrates a complete data science workflow using real-world space launch data from SpaceX.

The goal of this project is to **predict whether a Falcon 9 first-stage booster will successfully land**, using a combination of **Python**, **SQL**, **data visualization**, and **machine learning techniques**.

Through this project, I applied the full data science process:
- **Web scraping** and **data wrangling** from multiple sources (HTML, CSV)
- **Exploratory data analysis** (EDA) using Matplotlib, Seaborn, and SQL
- **Geospatial analysis** using Folium
- **Interactive dashboard** development using Plotly Dash
- **Supervised learning** with classification models like Logistic Regression, SVM, and Decision Tree  
- **Hyperparameter tuning** with GridSearchCV  
- **Model evaluation** with accuracy scores and visual comparisons

This repository is designed to be fully reproducible, modular, and readable for future learning, team collaboration, or presentation purposes.

---

## 🎯 Objectives

- Predict whether a Falcon 9 booster will successfully land or not.
- Identify key variables that impact landing success (e.g. payload, launch site).
- Perform SQL-based analysis, geospatial visualization, and machine learning.
- Build interactive dashboards and maps to support decision-making.

---

## 🧠 Technologies Used

- **Languages:** Python, SQL  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Dash, Folium, Scikit-learn, BeautifulSoup  
- **Tools:** Jupyter Notebook, IBM Db2, Git, VS Code  
- **Techniques:** Data Wrangling, EDA, Classification (Logistic, SVM, Decision Tree), SMOTE, GridSearchCV, Web Scraping

---

## 📁 Project Structure

| No | Notebook/Script                                     | Description                                                                 |
|----|-----------------------------------------------------|-----------------------------------------------------------------------------|
| 1  | [01_Data_Cleaning.ipynb](./01_Data_Cleaning.ipynb)  | Clean raw data from multiple sources (CSV, HTML)                            |
| 2  | [02_Data_Wrangling.ipynb](./02_Data_Wrangling.ipynb)| Merge, format, and structure data for analysis                              |
| 3  | [03_Web_Scraping.ipynb](./03_Web_Scraping.ipynb)    | Scrape payload data using BeautifulSoup from Wikipedia                      |
| 4  | [04_Exploring_and_Preparing_Data.ipynb](./04_Exploring_and_Preparing_Data.ipynb) | Exploratory analysis & feature engineering                         |
| 5  | [05_SQL_Analysis.ipynb](./05_SQL_Analysis.ipynb)     | SQL queries on IBM Db2 to analyze launch success trends                     |
| 6  | [06_Interactive_Dashboard_App.ipynb](./06_Interactive_Dashboard_App.ipynb) | Dash app with interactive plots by site/payload                  |
| 7  | [07_Geospatial_Analysis_with_Folium.ipynb](./07_Geospatial_Analysis_with_Folium.ipynb) | Map-based visualizations of launch sites                                   |
| 8  | [08_Machine_Learning_Model_Training.ipynb](./08_Machine_Learning_Model_Training.ipynb) | Train predictive models with 94% accuracy                                  |

---

## 🔍 Key Results

- ✅ Achieved **94% accuracy** in predicting booster landing success using Logistic Regression  
- 📊 Coastal launch sites showed **30% higher success rates**  
- 🌍 Geospatial mapping indicated **15% fuel savings** for launches near the equator  
- 🧠 Improved class balance using **SMOTE** to reduce false negatives

---

## 📊 Dashboard Preview

Interactive dashboard showing launch success rate by site and payload range.

**1. Pie Chart — Launch Success by Site**  
![Dashboard Pie](https://github.com/Rpfitrah/Data-Science-Capstone/blob/main/Image/dashboard-success-pie.jpg)

**2. Scatter Plot — Payload vs Success**  
![Dashboard Scatter](https://github.com/Rpfitrah/Data-Science-Capstone/blob/main/Image/dashboard-payload-correlation.jpg)

---

## 🗺️ Geospatial Launch Map

Interactive Folium map showing the success (green) and failure (red) outcomes at different launch sites.

![Map](https://github.com/Rpfitrah/Data-Science-Capstone/blob/main/Image/Lunch%20Site%20Map.jpg)

---

## 📚 Acknowledgements

This project is part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) on Coursera.  
Data sourced from SpaceX public datasets and Wikipedia.

---

## 👩‍💻 Author

**Fitrah Rahmi Putri, S.Kom**  
📧 Email: fitrah.rahmi.putri@gmail.com  
🔗 LinkedIn: [fitrah-rahmi-putri](https://www.linkedin.com/in/fitrah-rahmi-putri-99711a157/)  
🔗 GitHub: [@Rpfitrah](https://github.com/Rpfitrah)

---

## 📝 License

This project is intended for educational purposes only. No license is attached.
