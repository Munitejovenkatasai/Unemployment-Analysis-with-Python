# Unemployment Analysis with Python

## Overview
Unemployment analysis focuses on understanding trends in unemployment across different regions in India. The analysis is based on datasets obtained from Kaggle and utilizes Python libraries like Pandas, Seaborn, Matplotlib, and Plotly for data processing and visualization.

The project highlights how the unemployment rate fluctuated significantly during the COVID-19 pandemic, offering insights into regional disparities and trends in employment.

---

## Dataset
The datasets used in this analysis can be downloaded from the following link:  
[Unemployment in India - Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

### Key Features of the Dataset:
- **Region:** State or region in India.
- **Date:** Date of observation.
- **Frequency:** Data collection frequency.
- **Estimated Unemployment Rate (%):** The unemployment rate as a percentage.
- **Estimated Employed:** The estimated number of employed individuals.
- **Estimated Labour Participation Rate (%):** The labour participation rate as a percentage.
- **Area:** Rural or Urban classification.
- **Geographical Data:** Longitude and latitude for mapping purposes (in some datasets).

---

## Steps in Analysis

### Data Cleaning:
1. Removed leading and trailing spaces from column names.
2. Identified and handled missing values.
3. Checked for duplicates and standardized data types.

### Exploratory Data Analysis (EDA):
1. **Descriptive Statistics:**
   - Summarized data distribution using `describe()` and `info()` functions.
   - Assessed column-wise missing values and data shapes.

2. **Regional Analysis:**
   - Calculated average unemployment rates for each region.
   - Identified states with the highest and lowest unemployment rates:
     - **Highest:** Tripura (28.35%)
     - **Lowest:** Meghalaya (4.80%)

3. **Visualizations:**
   - **Bar Charts:** Displayed regional unemployment rates and labour participation rates.
   - **Box Plots:** Showed the spread of unemployment and labour participation rates across regions.
   - **Histograms:** Illustrated the distribution of unemployment rates, employment, and participation rates.
   - **Scatter Plots:** Explored relationships between unemployment rates and labour participation rates.

### Advanced Visualizations:
1. **Plotly Dashboards:**
   - Animated bar charts to observe changes in unemployment over time.
   - Line plots for unemployment trends.
   - Scatter plots to correlate variables like employment and unemployment.
   
2. **Seaborn Count Plots:**
   - Highlighted the distribution of data across areas (urban/rural) and regions.

---

## Key Insights:
1. **Unemployment Rates:**
   - Significant regional variations exist, with some states performing better than others.
   - The unemployment rate surged during COVID-19 but showed variability in recovery.

2. **Labour Participation:**
   - States with higher labour participation rates tend to have lower unemployment rates.
   - Urban areas had slightly better employment conditions compared to rural areas.

3. **Correlations:**
   - A negative correlation was observed between unemployment rates and labour participation rates.

---

## Libraries Used:
- **Data Handling:** `pandas`, `numpy`
- **Visualization:** `seaborn`, `matplotlib`, `plotly`

---

## Future Work:
1. Use machine learning models to predict unemployment rates based on historical data.
2. Include additional socioeconomic indicators to deepen insights.
3. Develop an interactive dashboard for real-time unemployment monitoring.

---

## Getting Started:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```
3. Run the notebook using Jupyter or Google Colab:
   ```bash
   jupyter notebook Unemployment_Analysis_with_Python.ipynb
   ```

--- 

## Author
This project was developed for educational purposes to explore unemployment trends in India using data science techniques.
