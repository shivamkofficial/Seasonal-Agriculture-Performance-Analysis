# Seasonal Agriculture Performance Analysis 🌾

A comprehensive analysis of seasonal agricultural performance using Python. This project explores crop yield, resource usage, environmental conditions, production costs, revenue, and farm profitability across different agricultural seasons and states in India.

## 📌 Project Overview

Agricultural performance varies according to season, environmental conditions, resource availability, crop selection, and economic factors. This project analyzes farm-level agricultural data to understand these variations and identify useful patterns in agricultural performance.

The analysis covers **4,000 farm records**, **28 variables**, **8 Indian states**, **8 crops**, and three major agricultural seasons: **Kharif, Rabi, and Zaid**.

The project uses Python-based data analysis and visualization techniques to compare agricultural performance and generate meaningful insights.

## 🎯 Objectives

* Explore and understand the agricultural dataset.
* Clean and prepare the data for analysis.
* Compare crop yield across different seasons.
* Analyze production cost, revenue, and profit.
* Study water, fertilizer, and pesticide usage.
* Examine environmental conditions such as rainfall, temperature, humidity, and soil conditions.
* Investigate relationships between agricultural conditions and outcomes.
* Compare agricultural performance across states and crops.
* Generate visual insights using charts and statistical analysis.
* Provide evidence-based recommendations and future scope.

## 📊 Dataset

The dataset contains **4,000 farm-level records** with **28 columns** covering farm information, environmental conditions, agricultural resources, production, and financial performance.

### Main Dataset Categories

**Farm Information**

* Farm ID
* State
* District
* Crop
* Season
* Farm Area

**Environmental Conditions**

* Rainfall
* Average Temperature
* Humidity
* Sunlight Hours
* Soil pH
* Soil Moisture

**Soil & Nutrients**

* Nitrogen
* Phosphorus
* Potassium

**Resource Usage**

* Irrigation Method
* Fertilizer Usage
* Pesticide Usage
* Seed Quality

**Agricultural Outcomes**

* Yield
* Production
* Market Price
* Total Cost
* Revenue
* Profit
* Water Used
* Water Efficiency
* Disease/Pest Risk

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **SciPy** – Statistical analysis
* **Jupyter Notebook** – Development and analysis environment

## 🔍 Analysis Performed

### 1. Data Exploration

The dataset was loaded and examined using Pandas. Dataset shape, data types, missing values, descriptive statistics, and sample records were analyzed.

### 2. Data Cleaning

The dataset was checked for missing values and data quality issues. Missing values in relevant numerical variables were handled before performing analysis.

### 3. Seasonal Performance Analysis

Agricultural performance was compared across:

* Kharif
* Rabi
* Zaid

Key performance measures included yield, cost, revenue, profit, and water efficiency.

### 4. Resource Usage Analysis

The project analyzes seasonal differences in:

* Water consumption
* Fertilizer usage
* Pesticide usage

This helps understand how resource requirements vary between agricultural seasons.

### 5. Environmental Analysis

Environmental variables were analyzed to understand seasonal patterns in:

* Rainfall
* Temperature
* Humidity
* Soil moisture
* Sunlight
* Soil pH

### 6. Crop-wise Analysis

Crop-level yield and seasonal performance were compared to identify differences among agricultural crops.

### 7. State-wise Profitability Analysis

Profitability was analyzed across Indian states to identify differences in economic performance.

### 8. Statistical Analysis

Statistical methods were used to investigate relationships between environmental/resource variables and agricultural outcomes.

## 📈 Visualizations

The project includes several visualizations, including:

* Seasonal KPI comparison charts
* Average water usage by season
* Average fertilizer usage by season
* Average pesticide usage by season
* Loss-making farm analysis
* Environmental condition boxplots
* Crop-wise yield comparison
* State-wise profit heatmap
* Water efficiency analysis

These visualizations make it easier to identify seasonal, crop-wise, and geographical patterns.

## 💡 Key Insights

The analysis helps identify:

* Differences in agricultural performance between Kharif, Rabi, and Zaid seasons.
* Variations in resource consumption across seasons.
* Differences in crop productivity.
* Differences in profitability between states and farms.
* Relationships between environmental conditions and agricultural outcomes.
* The importance of efficient water and resource utilization.

The exact numerical findings and conclusions are presented in the Jupyter Notebook and project presentation.

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
└── visualizations/
```

## ▶️ How to Run the Project

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project folder

```bash
cd Seasonal-Agriculture-Performance-Analysis
```

### Step 3: Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open:

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

Make sure the dataset file is in the same project directory:

```text
seasonal_agriculture_performance_dataset.csv
```

Then run the notebook cells sequentially.

## 🚀 Future Scope

The project can be further improved by:

* Developing machine learning models for crop yield prediction.
* Predicting farm profitability using historical data.
* Building an agricultural recommendation system.
* Adding real-time weather information.
* Developing an interactive dashboard using Power BI, Tableau, or Streamlit.
* Improving water and fertilizer optimization.
* Developing early-warning systems for disease and pest risks.
* Expanding the dataset to include more states, crops, and years.

## 📌 Project Type

**Major Project – VOIS AICTE Batch 1, 2026–2027**

## 👨‍💻 Author

**Student Name: SHIVAM KUMAR**

**College: SUYASH INSTITUTE OF INFORMATION TECHNOLOGY GORAKHPUR**

**AICTE Student ID: STU6a1838239276c1779972131**

---

⭐ If you find this project useful, consider giving the repository a star.
