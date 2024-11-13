**Strategic Expansion of Biogenesys**

# Introduction

BIOGÉNESYS, a pharmaceutical company, is undertaking a strategic initiative to identify optimal locations for the expansion of pharmaceutical laboratories. This decision is based on a comprehensive data analysis of COVID-19 incidence, vaccination rates, and the availability of healthcare infrastructure. The goal is to enhance pandemic and post-pandemic responsiveness to improve vaccine access.

# Project Development

## Progress 1

In the initial phase, data loading, transformation, and cleaning were conducted to support Biogenesys' strategic expansion into Latin America.

### 1. Summary of Progress
The following tasks were completed:
- Analyzed `Readme.txt` to understand dataset column descriptions.
- Created a notebook (`PIDA_M4_Nombre_Apellido.ipynb`) and imported libraries (Pandas, Numpy, Matplotlib).
- Loaded `data_latinoamerica.csv` and verified data integrity.
- Selected key countries: Colombia, Argentina, Chile, Mexico, Peru, and Brazil.
- Filtered data to include entries post-January 1, 2021.
- Addressed missing values by country comparison.
- Conducted preliminary data cleaning.
- Saved filtered data to CSV for future use.
- Calculated descriptive statistics for each dataset column.

### 2. Metric Analysis
*Implications*: Calculated metrics reveal insights into the distribution and behavior of dataset variables, supporting understanding of central tendency, variability, dispersion, and data shape, which are essential for further analysis.

### Conclusion
This initial phase laid the groundwork by preparing and cleaning data critical for Biogenesys’ expansion strategy in Latin America.

## Analysis of Measures 📉
- **Median**: Represents the central value in an ordered dataset, crucial for identifying central tendency without the influence of outliers.
- **Variance and Range**: High variance indicates data dispersion; a high range suggests significant variation among data values.

*Interpretation*: The combined analysis of median, variance, and range helps assess data consistency and variability.

## Extra Credit: Higher-Order Functions for Efficient Data Manipulation
High-order functions enhance flexibility and efficiency in data processing, allowing for more concise, reusable, and efficient code.

*Example*: The `calcular_tasa_incidencia(casos, poblacion)` function calculates and visualizes COVID-19 incidence rates, helping assess relative pandemic impacts across countries.

## Progress 2

### Exploratory Data Analysis and Visualization

This phase involved data exploration and visualization related to COVID-19 incidence, vaccination rates, and healthcare infrastructure. Key tasks included:
- Data manipulation and statistical analysis with Pandas and Numpy.
- Creation of visualizations (density histograms, bar charts, heatmaps, scatter plots) with Matplotlib and Seaborn to highlight patterns, trends, and anomalies.

## Progress 3

**Detailed EDA with Numpy and Pandas**

An advanced exploratory data analysis (EDA) was conducted to refine and prepare data for visualization, focusing on COVID-19 incidence patterns. Key steps included:
- Data pre-processing (handling missing values, date conversion).
- Temporal analysis (identifying active, recovered, confirmed case trends).
- Analysis of seasonality and autocorrelation in confirmed cases.

*Results*: EDA revealed patterns and correlations, essential for accurate forecasting and strategic site selection.

*Recommendations*: Continue advanced analysis, including spatial and temporal visualization, for strategic insights.

## Progress 4

**Practical Applications - Power BI Integration**

The final phase focuses on integrating and presenting analytical findings in Power BI. Dashboards and interactive reports were created to facilitate decision-making for laboratory expansion and vaccination center placement.

*Methodology*:
- Imported pre-processed data into Power BI for visualization.
- Designed interactive dashboards to effectively communicate data insights.

**Conclusions**:
This project provided a robust foundation for Biogenesys’ strategic expansion by leveraging data-driven insights into COVID-19 impact, healthcare capacity, and population vulnerability.
 
