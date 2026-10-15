# 📊 PhonePe Digital Payments Case Study

## 🔎 Project Overview

This project analyzes multi-year transaction and demographic data from
PhonePe across Indian states and districts.\
The objective is to extract meaningful business insights by performing
structured data loading, exploratory data analysis (EDA), data
validation, demographic correlation, and visualization.

The dataset spans from **Q1 2018 to Q2 2021** and includes:

-   State-level transactions and users
-   Transaction type splits
-   Device brand usage
-   District-level transaction data
-   District-level demographic data

------------------------------------------------------------------------

# 📌 Task 1: Data Loading and Understanding

## 1.1 Data Loading

-   Loaded all Excel sheets into pandas DataFrames.
-   Displayed sample rows (head, tail, middle).
-   Verified structure and column names.

## 1.2 Basic Statistics and Data Types

-   Generated summary statistics (mean, median, std, min, max).
-   Checked data types of each column.
-   Identified numerical and categorical fields.

## 1.3 Missing Values Analysis

-   Checked for missing values in all datasets.
-   Calculated percentage of missing values.
-   Identified columns with highest missing percentages.

## 1.4 Summary Statistics

-   Calculated total number of states and districts.
-   Identified the state with the highest number of district records.

------------------------------------------------------------------------

# 📊 Task 2: Exploratory Data Analysis (EDA)

## 2.1 Transaction Trends by State

-   Aggregated total transactions and total amount by state.
-   Identified top 5 and bottom 5 states by transaction volume.

## 2.2 Most Common Transaction Type

-   Determined the dominant transaction type for each state and quarter.
-   Observed Peer-to-Peer and Merchant payments as major contributors.

## 2.3 Device Brand Analysis

-   Identified device brand with highest registered users per state.
-   Found Android brands (Xiaomi, Samsung, Vivo) dominating.

## 2.4 Top District by Population

-   Identified the most populated district per state.
-   Visualized via column chart.

## 2.5 Average Transaction Value (ATV)

-   Computed ATV = Total Amount / Total Transactions.
-   Identified top 5 highest and lowest ATV states.

## 2.6 App Usage Trends

-   Aggregated total app opens by state and time.
-   Observed strong growth trend post-2019.

## 2.7 Transaction Type Distribution

-   Created bar chart for latest quarter distribution.
-   Merchant payments gaining significant share.

## 2.8 District Mapping

-   Created unique district name and code mapping.
-   Exported mapping as CSV file.

------------------------------------------------------------------------

# ✅ Task 3: Data Quality Checks

-   Aggregated district-level data and compared with state-level totals.
-   Verified consistency across aggregation levels.
-   Identified minor discrepancies due to rounding or data updates.

------------------------------------------------------------------------

# 🔄 Task 4: Data Merging and Advanced Analysis

## 4.1 User to Population Ratio

-   Merged user data with demographic data.
-   Calculated penetration ratio per state.
-   Identified mature vs emerging digital markets.

## 4.2 Density vs Transactions Correlation

-   Merged district transaction and demographic datasets.
-   Calculated correlation (\~0.30 moderate positive).
-   Density influences transactions but is not sole driver.

## 4.3 Average Transaction Amount per User

-   Computed total amount divided by registered users.
-   Identified high-value states.

## 4.4 Device Brand Usage Ratio

-   Calculated brand share per state.
-   Confirmed Android ecosystem dominance.

------------------------------------------------------------------------

# 📈 Task 5: Data Visualization

## 5.1 Time Series Analysis

-   Created line plots for transactions and amount over time.
-   Observed exponential growth from 2018 to 2021.

## 5.2 Pie Chart Analysis

-   Visualized transaction type distribution for selected state and
    quarter.

## 5.3 Population Density Visualization

-   Plotted district-wise population density for selected state.

------------------------------------------------------------------------

# 🧠 Task 6: Insights and Conclusions

## 6.1 Key Trends Identified

-   Strong year-over-year growth.
-   Post-COVID digital acceleration.
-   Merchant payment expansion.
-   Urban districts dominate transactions.
-   Android device dominance.

## 6.2 Demographic Correlation Findings

-   Weak-to-moderate positive correlation between density and
    transaction volume.
-   Digital adoption driven more by economic activity than density
    alone.

## 6.3 Strategic Recommendations

-   Focus on low penetration states for expansion.
-   Launch financial products in high ATV states.
-   Increase merchant onboarding in urban districts.
-   Partner with Android OEMs for user acquisition.

------------------------------------------------------------------------

# 🏆 Conclusion

This project demonstrates end-to-end data analytics capabilities
including: - Data cleaning - Exploratory analysis - Statistical
evaluation - Data validation - Correlation analysis - Business insight
generation - Visualization and reporting

The analysis reveals strong digital growth patterns and provides
actionable business recommendations for scaling digital payment adoption
across India.

------------------------------------------------------------------------

**Author:** Tushar Gupta\
**Tools Used:** Python, Pandas, Matplotlib
