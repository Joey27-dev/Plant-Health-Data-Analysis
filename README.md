# Plant-Health-Monitoring
Data analysis of plant health with visualizations and decision tree modeling using Python and Power BI.

# Plant Health Monitoring — Data Analysis & Power BI Dashboard

## Project Overview
This project aims to explore sensor-collected data on plant health using Python (Jupyter Notebook) and Power BI. Through exploratory data analysis I was able to identify the key environmental factors that affect plant stress levels — categorized into **Healthy**, **Moderate Stress**, and **High Stress** — and visualize these insights effectively for data science.

---

## Dataset Summary

| Feature Category      | Features Included                                                                 |
|-----------------------|-----------------------------------------------------------------------------------|
| Metadata              | `Timestamp`, `Plant_ID`                                                           |
| Sensor Readings       | `Soil_Moisture`, `Ambient_Temperature`, `Soil_Temperature`, `Humidity`, `Light_Intensity`, `Soil_pH` |
| Nutrient Levels       | `Nitrogen_Level`, `Phosphorus_Level`, `Potassium_Level`                          |
| Plant Health Markers  | `Chlorophyll_Content`, `Electrochemical_Signal`                                  |
| Target Variable       | `Plant_Health_Status` (`Healthy`, `Moderate Stress`, `High Stress`)              |

---

## Machine Learning

- **Model Used:** `DecisionTreeClassifier` from scikit-learn
- **Goal:** Predict `Plant_Health_Status` based on environmental and physiological data
- **Feature Importance Results:**
  - **Most Important Feature:** `Soil_Moisture`
  - **Second Most Important Feature:** `Nitrogen_Level`
  - Remaining features contributed < 1% each

---

## Visualizations (Jupyter Notebook)

- **Pie Chart:** Plant health distribution for:
  - `Soil Moisture < 20%`
  - `Soil Moisture > 30%`
- **Bar Graph:** Distribution of health status or feature values
- **Heatmap:** Correlation between `Humidity` and `Soil Moisture`
- **Scatter Plots:**
  - `Temperature Difference (Ambient - Soil)` vs `Plant_Health_Status`
  - `Soil_pH` across different health statuses
- **Partial Dependence Plot:**
  - Shows influence of `Nitrogen_Level` on predicted plant health

---

## Power BI Dashboard

Created an interactive dashboard to extend the analysis for non-technical stakeholders:

- **Q&A Panel:** Natural language interaction with the data
- **Display Matrix:** Tabular view of plant health by sensor readings
- **Key Influencers Visual:** Identifies top features affecting health status
- **Pie Chart:** Visual breakdown of health statuses
- **Bar Graph:** Nutrient levels across plant conditions

---

## Tools & Technologies

- **Language & Libraries:** Python, pandas, matplotlib, seaborn, scikit-learn
- **Notebook Environment:** Jupyter Notebook
- **BI Tool:** Microsoft Power BI
- **Other Tools:** NumPy, Plotly (if used)

---

## Key Takeaways

- Soil Moisture and Nitrogen are the most critical indicators of plant stress.
- Power BI enhances storytelling and allows for interactive exploration.
- Combining machine learning with visualization can yield actionable insights in agriculture.

---

## Future Improvements

- Deploy a web app with live predictions
- Incorporate time series analysis for trend tracking
- Integrate weather APIs for more contextual modeling

---

## Author

**Joash Austin Pillay**  
[LinkedIn - Joash Pillay](https://www.linkedin.com/in/joashpillay) • [GitHub: Joey27-dev](https://github.com/Joey27-dev) • [Email: joashaustinpillay27@gmail.com](joashaustinpillay27@gmail.com)

