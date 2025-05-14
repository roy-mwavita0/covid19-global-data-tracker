# 🌍 COVID-19 Global Data Tracker

## 📖 Project Description

This project analyzes global COVID-19 data to track trends in cases, deaths, recoveries, and vaccinations across countries and time. Using Python data tools, we clean and process real-world datasets, conduct exploratory data analysis (EDA), generate insights, and visualize trends.

By the end of the project, we develop a detailed data analysis report with charts, narrative explanations, and insights suitable for presentation or publishing.

---

## 🚩 Project Objectives

- ✅ Import and clean COVID-19 global data
- ✅ Analyze time trends (cases, deaths, vaccinations)
- ✅ Compare key metrics across countries and regions
- ✅ Visualize trends using charts and maps
- ✅ Communicate findings through a Jupyter Notebook or PDF report

---

## 🗂️ Project Segments

### 1️⃣ Data Collection
**Source:**  
- [Our World in Data (OWID)](https://github.com/owid/covid-19-data)  
- Johns Hopkins University (JHU) COVID-19 GitHub Repository

We used the `owid-covid-data.csv` for analysis due to its ease of use and well-structured data.

### 2️⃣ Data Loading & Exploration
- Load the dataset using `pandas.read_csv()`
- Inspect structure using `.head()`, `.columns`, and `.isnull().sum()`
- Focus on key columns like `date`, `location`, `total_cases`, `total_deaths`, `total_vaccinations`, etc.

### 3️⃣ Data Cleaning
- Filter for countries of interest (e.g., Kenya, USA, India)
- Convert `date` column to datetime format
- Handle missing values using `fillna()` and `interpolate()`

### 4️⃣ Exploratory Data Analysis (EDA)
- Plot total cases and deaths over time
- Compare new daily cases across selected countries
- Calculate death rate as `total_deaths / total_cases`
- Use line and bar charts to highlight trends

### 5️⃣ Visualizing Vaccination Progress
- Plot vaccination rollout over time
- Compare percent of population vaccinated
- Visualize using line charts and optional pie charts

### 6️⃣ Optional: Choropleth Map
- Use Plotly or GeoPandas to map total cases or vaccination rates by country
- Prepare data with `iso_code` and the most recent case data

### 7️⃣ Insights & Reporting
- Write 3–5 key insights from the data
- Highlight anomalies and trends
- Include markdown cells for narrative and reflections

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- [Jupyter Notebook](https://jupyter.org/)
- pandas
- matplotlib
- seaborn
- Optional: plotly, geopandas

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/covid19-global-data-tracker.git
