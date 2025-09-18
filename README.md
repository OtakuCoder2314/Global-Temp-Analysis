# 🌡️ Global Temperature Analysis

This project focuses on **time-series analysis of global land-ocean temperature anomalies** using the [DataHub Global Temp dataset](https://datahub.io/core/global-temp).  
The goal is to visualize long-term warming trends, perform exploratory data analysis (EDA), and derive insights about climate change.

---

## Dataset  

- **Source:** [DataHub Global Temp dataset](https://datahub.io/core/global-temp)
- **Coverage:** Monthly global temperature anomalies (°C), 1850 – Present  
- **Columns:**  
  - `Source` → Dataset origin (e.g., GCAG)  
  - `Year` → Year and Month in `YYYY-MM` format  
  - `Mean` → Monthly global temperature anomaly (relative to baseline)  

---

## Objectives
- Clean and preprocess global temperature data for analysis.
- To visualize long-term trends in global temperature anomalies.
- To generate smoothed trends using moving averages.
- Identify seasonal variations in temperature patterns.
- Interpret findings related to global climate change.
  

---

## Methodology
1. **Data Collection**:
   - Monthly global temperature anomaly data was collected from NOAA.
3. **Data Cleaning & Preprocessing**:
   - Converted the Year column from YYYY-MM to datetime format.
   - Extracted separate Year and Month fields.
   - Handled missing values and ensured data consistency.
   - Sorted records chronologically.
4. **Data Analysis**:
   - Generated line plots of temperature anomalies by source.
   - Computed 12-month moving averages for smoothing fluctuations.
   - Created a seasonal heatmap of temperature patterns over the last 50 years.
5. **Tools & Libraries Used**:
   - Python, Pandas, Matplotlib, Seaborn. 
   - Jupyter Notebook / Google Colab  

---

## Results  

The analysis of the monthly global temperature dataset produced the following key findings:  

- **Long-term Trend:** Global temperatures have shown a steady increase, especially after the mid-20th century.  
- **Smoothed Analysis:** A 12-month moving average clearly highlights the warming trend, filtering out short-term fluctuations.  
- **Seasonal Patterns:** Heatmap visualization of the last 50 years indicates consistently warmer temperatures across most months, with recent decades showing more intense warming.  

### Visual Highlights  
- **Line Plot of Monthly Temperature Anomalies** – Shows fluctuations in global temperature across years.  
- **12-Month Moving Average Trend** – Demonstrates a clear upward trajectory in global warming.  
- **Seasonal Heatmap (Last 50 Years)** – Highlights warming patterns across different months and years.  

 **Conclusion:**  
The results confirm a consistent rise in global temperatures, aligning with scientific consensus on climate change.  

---
