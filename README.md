# COVID-19 Data Visualization 📊

This project presents an in-depth **Exploratory Data Analysis (EDA)** and **Visualization** of global COVID-19 trends using the dataset `covid_19_data.csv`. The analysis was performed in **Python** using **Pandas**, **Seaborn**, and **Matplotlib** libraries, and executed on **Google Colab**.

---

## 📁 Dataset Information

- **File**: `covid_19_data.csv`
- **Source**: [Johns Hopkins University COVID-19 Data Repository]
- **Columns**:
  - `SNo`, `ObservationDate`, `Province/State`, `Country/Region`
  - `Last Update`, `Confirmed`, `Deaths`, `Recovered`

---

## 🔍 Key Objectives

- Handle missing data and clean the dataset.
- Perform time series analysis of confirmed, deaths, recovered, and active cases.
- Visualize country-level trends and compare fatality rates.
- Identify top 10 countries based on various COVID-19 metrics.
- Analyze and compare trends in specific countries like **USA** and **Italy**.
- Understand relationships between key indicators (Confirmed vs Deaths, etc.)

---

## 📊 Visualizations Performed

1. **Global Trends Over Time**
   - Confirmed, Deaths, and Recovered cases
   - Active cases trend
   - Daily new confirmed, deaths, recovered

2. **Country-wise Analysis**
   - Top 10 countries by Confirmed, Deaths, and Recovered cases
   - Country-specific time trends (USA, Italy)
   - Fatality rate analysis

3. **Scatter Plots**
   - Confirmed vs Deaths (log scale)
   - Confirmed vs Recovered (log scale)

4. **Heatmap**
   - Correlation matrix of COVID-19 metrics

5. **Distribution Plot**
   - Fatality Rate distribution across countries with >1000 cases

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 📌 How to Run

1. Clone the repository or download the files
2. Open `covid19_visualization.ipynb` in Google Colab or Jupyter
3. Make sure `covid_19_data.csv` is in the same directory
4. Run the cells sequentially to view the analysis and visualizations

---

## 🧠 Insights

- The USA has the highest confirmed and death counts
- Fatality rates are highest in countries with overwhelmed healthcare
- Active cases peaked mid-2020 and started to decline as recoveries rose

---

## 📬 Author

**Lokesh Meshram**  
Third Year Computer Engineering, PCCOE  
Submitted as part of **Assignment 3 – Data Visualization**

---

## 🏷️ Tags

`#COVID19` `#Visualization` `#Python` `#Pandas` `#Seaborn` `#Matplotlib` `#Colab`
