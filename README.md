# Airbnb Listings Analysis: Chicago vs New Orleans

A comparative data analytics project exploring Airbnb listings in **Chicago** and **New Orleans** using Python, Pandas, and Power BI.

## Project Overview

This project analyzes Airbnb listing data from Chicago and New Orleans to understand differences in property distribution, pricing patterns, neighbourhood popularity, customer reviews, and host characteristics.

The project combines Exploratory Data Analysis (EDA), data cleaning, feature engineering, and interactive Power BI dashboards to convert raw listing data into meaningful insights.

## Project Objectives

- Compare Airbnb listing counts across both cities.
- Identify popular neighbourhoods based on listing concentration.
- Analyze room type and property type distributions.
- Compare average and median listing prices.
- Explore relationships between host categories, prices, and reviews.
- Build an interactive dashboard for business-oriented analysis.

## Tools and Technologies

- **Python:** Data analysis and preprocessing
- **Pandas & NumPy:** Data cleaning and transformation
- **Matplotlib & Seaborn:** Exploratory data analysis and visualization
- **Power BI:** Interactive dashboard development
- **Google Colab:** Notebook execution
- **GitHub:** Project documentation and version control

## Repository Structure

```text
Airbnb-Chicago-vs-New-Orleans/
│
├── Airbnb_Chicago_vs_New_Orleans_EDA.ipynb
├── Airbnb_Dashboard.pbix
├── airbnb_chicago_new_orleans_cleaned.csv
├── data_quality_summary.csv
└── README.md
```

## Data Cleaning and Transformation

The following preprocessing steps were performed:

- Removed duplicate listing records within each city.
- Standardized column names and text values.
- Converted price values into numeric format.
- Handled invalid and missing price values.
- Converted date and numeric columns into appropriate data types.
- Validated availability values.
- Created analytical categories for price, availability, reviews, and host types.

Missing prices were retained as null values instead of being replaced with zero.

## Power BI Dashboard

The Power BI report contains four analytical pages:

### 1. Overview
- Total listings
- Unique hosts
- Average listing price
- Average reviews
- City-wise comparison
- Room type distribution
- Top neighbourhoods

### 2. Property Analysis
- Room type distribution
- Property type distribution
- Top neighbourhoods by listing count
- Listings by city and room type
- Accommodation capacity
- Price category distribution

### 3. Pricing Analysis
- Average price by city
- Average price by room type
- Average price by property type
- Average price by neighbourhood
- Price category distribution

### 4. Host Analysis
- Unique hosts by city
- Listings by host category
- Average price by host category
- Average reviews by host category
- Top hosts by listing count

## How to Run the Project

1. Download or clone this repository.
2. Open the EDA notebook in Google Colab or Jupyter Notebook.
3. Upload the original Chicago and New Orleans Airbnb listings CSV files when prompted.
4. Execute the notebook cells sequentially.
5. Review the EDA results and generated visualizations.
6. Open `Airbnb_Dashboard.pbix` using Microsoft Power BI Desktop.

**Dataset source:** [Inside Airbnb – Get the Data](https://insideairbnb.com/get-the-data/)

## Important Limitations

- The two city datasets have different snapshot dates, which may affect direct comparisons.
- Some listings have missing price values.
- Availability represents calendar availability, not actual occupancy or booked nights.
- Listing prices should not be interpreted as actual revenue.
- Correlation between variables does not establish causation.
- Price, availability, review, and host categories use analytical thresholds created for this project.

## Conclusion

This project demonstrates how raw Airbnb listing data can be cleaned, explored, transformed, and presented through interactive business intelligence dashboards.

The comparative analysis provides insights into listing distribution, property characteristics, pricing patterns, neighbourhood concentration, and host behaviour across Chicago and New Orleans.

---

**Project Category:** Data Analytics | Exploratory Data Analysis | Business Intelligence

**Dashboard Tool:** Microsoft Power BI

**Notebook:** Python / Google Colab
