# 📊 COVID-19 Data Analysis Report

### 🔍 Project Objective

This project aim to explore, visualize, and analyze global COVID-19 trends over time, with a focus on comparing case numbers, deaths, and growth patterns across different continents and countries. The goal is to identify meaningful patterns and insights that can help understand the impact and progression of the pandemic. Therefore, we

- Analyze total and new COVID-19 cases over time.
- Compare pandemic trends across continents.
- Visualize 7-day rolling averages and fatality rates.
- Identify top countries with highest new cases.
- Generate insightful charts for reporting.

### 📦 Data Source

- **Dataset**: Our World in Data 'OWID' CSV file

[Link to download](https://covid.ourworldindata.org/data/owid-covid-data.csv)

- **Columns Used**: `date`, `location`, `continent`, `new_cases`, `total_cases`, `total_deaths`

### ✅ Tools Used

- `pandas` for data manipulation  
- `matplotlib` & `seaborn` for visualization  
- `jupyter` for analysis workflow

### Data Analysis

```Python
# Load data
url = 'https://covid.ourworldindata.org/data/owid-covid-data.csv'
df = pd.read_csv(url)

# Explore data
print(df.head())
print(df.columns);

etc.
```
### 📈 Visualizations

#### 1. Total COVID-19 Cases by Continent Over Time

[Total COVID 19 cases by continent](https://github.com/user-attachments/assets/6b0212fe-437e-4f9e-a67c-4ff80a7b2c48)

#### 2. 7-Day Rolling Average of New COVID-19 Cases by Continent

[7-DR Avr covid 19](https://github.com/user-attachments/assets/f9aa6b77-9c2c-454c-9e0e-83fc1952c207)

#### 3. COVID-19 Case Fatality Rate by Continent Over Time

[Fatality rate](https://github.com/user-attachments/assets/14b8f1fc-04d2-4420-8d13-3f07d2b09aab)

#### 4. Total COVID-19 Cases by Continent and Month (Heatmap)

[Total covid 19 continent cases per month](https://github.com/user-attachments/assets/1b20c0ea-fa59-444f-af84-2777b3596f47)


#### 5. Top 5 Countries by New COVID-19 Cases (Latest Date)

[Top_5_countries](https://github.com/user-attachments/assets/51abf262-5588-41bd-b72c-1ed89b56517b)


### 📌 Insights
- **Asia and Europe** had high total case counts over time.
- **7-day rolling averages** reveal wave-like patterns.
- Fatality rates varied, but trended downward globally.
- **India, USA, Brazil** frequently appear among top 5 countries by new cases.





