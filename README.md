## Keystone Homes: Student Housing Demand & Rent Analysis
# Overview

This project analyzes student housing demand and rental market dynamics to support data-driven acquisition and pricing decisions for Keystone Homes, a student-focused housing concept. The analysis examines how changes in student enrollment, particularly international enrollment, relate to rent trends and housing demand in the Greater Boston area.

Rather than treating student housing demand as static, the project frames it as a responsive system influenced by demographic shifts, market supply, and neighborhood-level rent patterns. The goal is to move beyond anecdotal assumptions and ground real estate and product decisions in quantitative analysis.

The work combines multiple public datasets and applies exploratory data analysis and regression techniques to surface relationships, limitations, and tradeoffs in the data.

# Potential Applications

This analysis is directly applicable to student housing operators, real estate investors, and urban planners. For Keystone Homes specifically, the framework can inform where to acquire properties, how to price units, and which submarkets are most sensitive to enrollment changes.

More broadly, the approach can be extended to other demand-driven housing segments where population trends materially impact rent, occupancy, and investment risk. The project also highlights how imperfect data can still be used responsibly to guide strategic decisions when assumptions are made explicit.

# Key Concepts

Student housing demand modeling
Rental market analysis
Exploratory data analysis (EDA)
Linear regression and trend analysis
Multi-source data integration
Interpreting correlation vs causation

# Repository Structure
```
keystone-homes-data-analysis/
├── KeystoneHomesDataAnalysis.ipynb
├── data/
│   ├── boston-fy2025-property-assessment-data_12_30_2024.csv
│   ├── boston-311-metadata.csv
│   ├── Census_Leading-Institutions-by-Institutional-Type_OD24_Website.xlsx
│   ├── zillow-all-homes-plus-multifamily-time-series-zipcode.csv
│   └── zip-codes-database-FREE.csv
├── README.md
```

# How to Run
Ensure Python and Jupyter Notebook are installed. Install required dependencies if needed:

pip install pandas numpy matplotlib seaborn scikit-learn

# Launch the notebook:

jupyter notebook KeystoneHomesDataAnalysis.ipynb
