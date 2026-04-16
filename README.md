# 🦠 COVID-19 Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a COVID-19 dataset to understand global trends in confirmed cases, deaths, recoveries, and other key indicators. The analysis includes data cleaning, feature engineering, visualization, correlation analysis, and outlier detection.

---

## 📂 Dataset Information
The dataset contains COVID-19 daily reports with the following features:

- Country_Region
- Confirmed
- Deaths
- Recovered
- Active
- Incident_Rate
- Case_Fatality_Ratio

---

## 🎯 Objectives
- Understand dataset structure
- Clean and preprocess data
- Handle missing and infinite values
- Perform statistical analysis
- Visualize COVID-19 trends
- Identify top affected countries
- Detect outliers
- Create new meaningful features

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📊 Exploratory Data Analysis Steps

### 1️⃣ Data Loading & Inspection
- Loaded dataset using pandas
- Checked shape, data types, and missing values

### 2️⃣ Data Cleaning
- Removed unnecessary columns
- Handled missing values using group-based imputation
- Replaced infinite values
- Filled null values

### 3️⃣ Feature Engineering
- Created Case Fatality Ratio (CFR)
- Created Case Level categories (Low, Medium, High)

### 4️⃣ Statistical Analysis
- Used describe() for summary statistics

### 5️⃣ Data Visualization
- Histograms for Confirmed, Deaths, Recovered
- Boxplots for top countries
- Countplot for country distribution
- Correlation heatmap

### 6️⃣ Outlier Detection
- Boxplot method
- Z-score method

### 7️⃣ Multivariate Analysis
- Pairplot for relationships between variables
- Facet-based analysis using case severity

---

## 📈 Key Insights
- Confirmed cases and deaths are strongly correlated
- Data is highly skewed across countries
- Few countries contribute most global cases
- Presence of significant outliers in confirmed cases
- Clear clustering based on severity levels

---

## 🚀 How to Run This Project

```bash
# Clone repository
git clone https://github.com/aveenjoseph04/Exploratory-data-analysis.git

# Move into project folder
cd covid19-eda

# Install dependencies
pip install -r requirements.txt

# Run notebook or script
👨‍💻 Author

Aveen Joseph
