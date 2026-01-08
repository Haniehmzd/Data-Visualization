# The Cost of Progress  
### A Trend Analysis of Wealth, Health, and Environment (1960–2020)

This project explores the relationship between economic growth, quality of life, and environmental impact across countries over time. Using publicly available data from the World Bank, the analysis investigates how increases in wealth relate to life expectancy and CO₂ emissions.

---

##  Research Questions

**Primary Question**
- How is economic growth related to quality of life and environmental impact across countries?

**Secondary Questions**
- Is higher GDP per capita associated with higher life expectancy?
- Does economic development lead to higher CO₂ emissions?
- How do these relationships differ across world regions?

---

##Data Sources

All data are sourced from the **World Bank – World Development Indicators (WDI)** and are publicly available under an open data license.

**Selected indicators:**
- GDP per capita  
- Life expectancy at birth  
- CO₂ emissions per capita  
- Population growth  

**Time period:** 1960–2020

---

##Data Processing

- Missing values were identified and handled, especially for earlier years.
- Multiple indicators were merged into a single dataset by country and year.
- GDP per capita values were log-transformed to reduce skewness and improve visualization clarity.
- Countries were grouped into world regions (Africa, Americas, Asia, Europe, Oceania).

---

## Methodology & Tools

- **Programming language:** Python  
- **Libraries:** pandas, numpy, seaborn, matplotlib  
- **Visualization tools:**  
  - Scatter plots for exploring relationships between GDP per capita and life expectancy  
  - Choropleth maps (Datawrapper) for CO₂ emissions per capita  

**Analytical techniques used:**
- Descriptive statistics  
- Correlation analysis  
- Trend analysis  
- Comparative regional analysis  

---

##  Key Insights

- Higher GDP per capita is generally associated with higher life expectancy.
- The relationship between income and life expectancy shows diminishing returns at higher income levels.
- CO₂ emissions per capita increase with economic development, particularly in industrialized regions.
- Developing regions exhibit rapid growth in CO₂ emissions over time.
- Strong regional disparities exist in economic, health, and environmental indicators.

---

##  Limitations

- Correlation does not imply causation.
- Some indicators contain missing values, particularly in earlier years.
- CO₂ emissions per capita do not capture all dimensions of environmental impact.

---

## Reproducibility

The analysis can be fully reproduced using the datasets and notebooks provided in this repository.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

## 👩‍🎓 Author

**Hanieh Mirzad**  
Data Visualization – Student Individual Assignment
