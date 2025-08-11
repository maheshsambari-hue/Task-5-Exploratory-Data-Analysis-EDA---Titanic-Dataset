# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## 📌 Objective
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns, trends, and relationships in the data.

## 🛠 Tools Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab** (for running the analysis)

## 📂 Dataset
- **Name:** Titanic Dataset
- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **Description:** Contains passenger details such as age, gender, ticket class, fare, and survival status.

## 🔍 Steps Performed
1. **Data Loading** – Imported dataset into Pandas DataFrame.
2. **Data Overview** – Used `.info()`, `.describe()`, `.value_counts()` to understand structure and summary.
3. **Data Cleaning** – Handled missing values, checked data types, and removed unnecessary columns if needed.
4. **Univariate Analysis** – Histograms, count plots for categorical variables.
5. **Bivariate Analysis** – Boxplots, scatterplots, and bar charts to explore relationships between variables.
6. **Correlation Analysis** – Heatmap to visualize relationships between numeric variables.
7. **Pair Plot** – Visualized relationships between multiple features.
8. **Observations** – Added insights below each visual.
9. **PDF Report** – Generated and saved all findings as a single PDF.

## 📊 Key Insights
- **Survival Rate:** Higher among females compared to males.
- **Class Factor:** Passengers in 1st class had higher survival rates than those in 3rd class.
- **Age Distribution:** Most passengers were between 20-40 years old.
- **Fare Impact:** Higher fares were correlated with higher survival rates.

## 📁 Files in This Repository
- `titanic_eda.ipynb` → Jupyter Notebook with full analysis.
- `titanic_eda.pdf` → PDF report containing visuals and observations.
- `README.md` → Project documentation.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sambarimahesh-hue/Task-5-Exploratory-Data-Analysis-EDA-Titanic-Dataset.git
