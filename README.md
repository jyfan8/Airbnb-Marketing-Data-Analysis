# 🏠 Airbnb Marketing Analysis

This repository contains an in-depth marketing and exploratory data analysis of Airbnb listings in Albany, New York. The project investigates user behavior, pricing patterns, seasonal trends, and provides actionable recommendations based on data-driven insights.

## 📊 Project Overview

**Objective**  
To analyze Airbnb's listings using data science techniques to uncover pricing trends, seasonal effects, room type distributions, and user engagement patterns. The project concludes with strategic marketing recommendations for business development.

**Tools & Technologies**  
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter Notebook  
- Data Sources: `calendar.csv`, `listings.csv`, `reviews.csv`

## 🧰 Dataset Information

The dataset, dated **September 5, 2024**, includes:
- `calendar.csv`: Pricing and availability per day
- `listings.csv`: Listing details (type, location, host info, etc.)
- `reviews.csv`: Customer reviews per listing

## 🧹 Data Preprocessing

Key preprocessing steps included:
- Standardizing column names and data types
- Handling missing/null values and duplicates
- Column transformations (splitting granular data)
- Merging datasets using primary key: `listing_id`

## 📈 Key Findings

- **Price Distribution**: Right-skewed; most prices clustered around \$150–160.
- **Room Types**: Majority are *Entire home/apt*, followed by *Private room*.
- **Seasonality**: Price peaks in December/January and dips in October/November.
- **Review Trends**: 2015 had a spike; significant drop in 2021–2022 (likely due to COVID-19).
- **Top Features for Pricing**: Location (latitude & longitude), availability, room type.

## 💡 Recommendations

- **Dynamic Pricing Strategy**: Adjust pricing based on demand and seasonality.
- **Target Neighborhood Focus**: Promote listings in high-demand areas (e.g., Sixth Ward).
- **Review Sentiment Monitoring**: Analyze October peak reviews for improvement opportunities.

## ✅ Outcome

This project offers a roadmap for how Airbnb can leverage its data to enhance customer satisfaction, improve listing visibility, and increase platform retention.


## 👤 Author

**Jing**  
Contributions: Data cleaning, EDA, Visualization, Strategy Recommendations

