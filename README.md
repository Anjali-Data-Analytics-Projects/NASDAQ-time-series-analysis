# Financial Time Series Analysis and Outlier Detection

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
## Project Overview
This project is dedicated to the comprehensive analysis of financial time series data across multiple companies. Its primary goal is to explore the data(EDA), extract actionable insights through advanced time series analysis, focusing on identifying underlying trends and detecting anomalies in financial metrics.
### Key Objectives:
* **User-Friendly Interface:**
  * Developed a **user-friendly interface** for easy access and interaction with the analysis results.
  * Ensuring that non-technical stakeholders can easily navigate and extract insights, enhancing overall engagement with the data.
* **Data Quality Assessment:**
  * **Conducted a rigorous data quality assessment** to ensure the reliability and validity of the data being analyzed.
  * **Cleansed the dataset** by handling missing values and correcting inconsistencies, ensuring a solid foundation for analysis.
* **Data Aggregation**
  * Employed robust techniques to aggregate financial data over various time frames—monthly, quarterly, and yearly.
  * Allowing for a nuanced understanding of trends, seasonal patterns, and growth trajectories, which are crucial for strategic planning.
* **Temporal Feature Creation:**
  * **Generated lagged features** to capture how historical data points influence current values of financial amounts.
  * Improving the predictive capabilities of models by **identifying time-dependent relationships**, essential for accurate forecasting.
* **Correlation Analysis**
  * Analyzed relationships and dependencies between original financial amounts and lagged features to determine correlations.
  * **Generated a correlation matrix** and **heatmap** to visualize these dependencies and further guide future predictive modeling.
* **Interactive Visualizations:**
  * Integrated **dynamic visualizations** using libraries such as Matplotlib and Seaborn to illustrate data patterns, trends, and outliers.
  * Empowering stakeholders to grasp complex financial narratives quickly and intuitively, making data-driven decisions more accessible.
* **Outlier Detection:**
  * **Utilized advanced statistical methods**, such as the **Interquartile Range (IQR) method** and **Z-score analysis**, to identify and analyze outliers.
  * Providing clarity on unusual data points that could skew results or indicate critical events, enhancing data reliability.
* **Impact Analysis: Sensitivity Analysis**
  * Conducted sensitivity analyses to understand **the effects of outlier removal on overall trends and insights.**
  * Provided visualizations to demonstrate how the dataset’s trends change pre- and post-outlier removal.
* **Reporting and Documentation:**
  * Generated comprehensive reports summarizing findings, methodologies, and recommendations for stakeholders.
  * Provided clear documentation to facilitate future enhancements and enable other analysts to build upon this work.
 
## Technologies Used
* **Programming Languages:** Python 3.x
* **Libraries:**
  * **Data Analysis Libraries**
     * **Pandas**
     * **NumPy** 
  * **Data Visualization Tools**
     * **Matplotlib** 
     * **Seaborn** 
  * **Statistical Analysis**
     * **Statsmodels**
     * **Scipy** 
  * **Time-Aggregation**
     * **Datetime & Resampling** 
  * **Data Acquisition**
     * **requests**
* **Version Control and Collaboration**
  * **Git** 
  * **GitHub** 
* **Development Environment**
  * **Jupyter Notebook** 
  * **VS Code** 

## Usage
To run the tool, use the following steps:
1. **Run the main script:**
2. **Follow the instructions in the command line:**
    *  A list of companies will be displayed. Enter the number corresponding to the company you want to analyze.               
    * The script will process the data and produce visualizations for data distribution, outlier detection, and temporal trends.             
3. **View the results:**
    *  After processing, multiple plots will be displayed, providing insight into the financial metrics of the selected company.             



## Results
* **Outlier Analysis**
A total of 161 outliers were identified using the IQR method.
After removing outliers, the financial amounts follow a smoother distribution, enabling more accurate trend analysis.
* **Correlation Analysis**
The lagged correlations with Amount_USD are weak across all periods (Lag_1, Lag_2, Lag_3), implying that past financial performance does not significantly influence current amounts.
Lag 1: 0.1120 (Weak correlation)
Lag 2: -0.1224 (Weak correlation)
Lag 3: -0.0287 (Weak correlation)
* **Visualization Insights**
Time series visualizations revealed significant seasonal patterns in financial performance, especially when aggregated monthly and quarterly.
Removing outliers showed more consistent trends, which helped in deriving actionable insights from the cleaned data.
* **Impact Analysis**
Sensitivity Analysis: Comparing original data with cleaned (outlier-free) data demonstrated that extreme outliers skew the trends. Removal of these outliers leads to smoother financial trends and more reliable insights.

## Conclusion
This project offers a robust framework for analyzing financial time series data, emphasizing the exploration of trends, effective outlier detection and handling, and the examination/investigation of historical relationships via lagged correlations, among key financial metrics revealing the underlying dynamics of financial performance over time.
The modular design allows for easy customization, enabling users to adapt the analysis for various datasets or extend it to include additional financial metrics or companies. 

