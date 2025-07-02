# 🚀 Data Science Capstone: Falcon 9 Landing Prediction & Analysis

This repository contains the final project of the **IBM Data Science Professional Certificate**.  
The objective is to analyze and predict the landing success of **SpaceX Falcon 9 first-stage boosters**, and present the results using interactive dashboards and visualizations.

---

## 🎯 Objectives

- Predict whether a Falcon 9 booster will successfully land or not.
- Identify key variables that impact landing success (e.g. payload, launch site).
- Perform SQL-based analysis, geospatial visualization, and machine learning.
- Build interactive tools to support decision-making.

---

## 🧠 Technologies Used

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Dash, Folium, Scikit-learn, BeautifulSoup
- **Tools:** Jupyter Notebook, IBM Db2, Git, VS Code
- **Techniques:** EDA, Classification, SMOTE, GridSearchCV, Web Scraping, Data Wrangling

---

## 📁 Project Structure

| No | Notebook/Script                                     | Description                                                                 |
|----|-----------------------------------------------------|-----------------------------------------------------------------------------|
| 1  | [01_Data_Cleaning.ipynb](./01_Data_Cleaning.ipynb)  | Clean raw data from multiple sources (CSV, HTML)                            |
| 2  | [02_Data_Wrangling.ipynb](./02_Data_Wrangling.ipynb)| Merge, format, and structure data for analysis                              |
| 3  | [03_Web_Scraping.ipynb](./03_Web_Scraping.ipynb)    | Scrape payload data using BeautifulSoup from Wikipedia                      |
| 4  | [04_Exploring_and_Preparing_Data.ipynb](./04_Exploring_and_Preparing_Data.ipynb) | Conduct exploratory analysis & feature engineering                        |
| 5  | [05_SQL_Analysis.ipynb](./05_SQL_Analysis.ipynb)     | Analyze launch data using SQL queries on IBM Db2                            |
| 6  | [06_Interactive_Dashboard_App.ipynb](./06_Interactive_Dashboard_App.ipynb) | Build a Dash app with interactive visualizations                          |
| 7  | [07_Geospatial_Analysis_with_Folium.ipynb](./07_Geospatial_Analysis_with_Folium.ipynb) | Visualize launch sites and success geographically                         |
| 8  | [08_Machine_Learning_Model_Training.ipynb](./08_Machine_Learning_Model_Training.ipynb) | Train predictive models (Logistic, SVM, Decision Tree)                    |

---

## 🔍 Key Results

- ✅ Achieved **94% accuracy** in predicting booster landing success using Logistic Regression.
- 📊 Coastal launch sites showed **30% higher success rates**.
- 🌍 Geospatial mapping indicated **15% fuel savings** for launches near the equator.
- 🧠 Reduced false negatives via **SMOTE** on imbalanced classes.

---

## 📊 Dashboard & Visuals

- Explore launch outcomes filtered by payload and site in a dynamic [Dash App](./06_Interactive_Dashboard_App.ipynb).
- View mapped launch sites with [Folium maps](./07_Geospatial_Analysis_with_Folium.ipynb).

---

## 📚 Acknowledgements

This project is part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) on Coursera.

---

## 👩‍💻 Author

**Fitrah Rahmi Putri, S.Kom**  
- LinkedIn: [fitrah-rahmi-putri](https://www.linkedin.com/in/fitrah-rahmi-putri-99711a157/)  
- GitHub: [@Rpfitrah](https://github.com/Rpfitrah)  
- Email: fitrah.rahmi.putri@gmail.com

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
