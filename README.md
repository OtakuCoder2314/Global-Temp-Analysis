# 🌡️ Global Temperature Anomaly Analysis

This project focuses on **time-series analysis of global land-ocean temperature anomalies** using the [DataHub Global Temp dataset](https://datahub.io/core/global-temp).  
The goal is to visualize long-term warming trends, perform exploratory data analysis (EDA), and derive insights about climate change.

---

## Dataset
- Source: [DataHub – Global Land and Ocean Temperature Index](https://datahub.io/core/global-temp)  
- Coverage: Monthly temperature anomalies (°C), 1880 – Present  
- Columns:  
  - `Source` → Dataset origin (GCAG or GISTEMP)  
  - `Date` → Month and Year  
  - `Mean` → Temperature anomaly relative to baseline  

---

## Objectives
- Clean and preprocess global temperature datasets.  
- Detect and visualize **long-term warming trends**.  
- Analyze **decade-wise averages** to measure acceleration of warming.  
- Apply **rolling averages** for smoothing trends.  
- Draw **data-driven conclusions** about climate change.  

---

## Methodology
1. **Data Preprocessing**  
   - Converted `Date` to datetime format  
   - Replaced missing values (`-999`) with NaN  
   - Filtered data from different sources (GCAG, GISTEMP)  

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Raw time-series visualization  

3. **Data Visualization**  
   - Line plots of anomalies over time  
   - Rolling 12-month averages  
   - Decade-wise bar charts  
   - Seasonal boxplots  

4. **Tools Used**  
   - Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)  
   - Jupyter Notebook / Google Colab  

---

## Results
- Clear **warming trend** observed, especially after the 1970s.  
- Rolling averages confirm **consistent global warming acceleration**.  
- Decade-wise analysis shows recent decades are significantly hotter than earlier periods.  
- Seasonal patterns reveal anomalies across months but with upward shift in recent years.  

---

