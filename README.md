# NYC_Airbnb_Price-Prediction-EDA-Project-Using-Python-

This project focuses on analyzing Airbnb listings in New York City to explore price patterns, uncover influential factors, and prepare the dataset for potential predictive modeling. It uses Python for data cleaning, exploration, visualization, and feature engineering.

![image alt](https://github.com/JISHNUPALIT/NYC_Airbnb_Price-Prediction-EDA-Project-Using-Python-/blob/2447b482522ff6803893f6dca0610cbc8a8cebbf/airbnb_NYC_image.jpg)


## 📌 Project Objective

To perform exploratory data analysis on New York Airbnb listings in order to:
- Understand key drivers of listing prices
- Visualize geographic and categorical trends
- Prepare the dataset for price prediction
- Engineer new features for improved insights

---

## 🧰 Tools & Technologies

- **Python 3**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis environment

---

## 📂 Dataset Overview

- **File**: `NewYork_airbnb_listings.csv`
- **Rows**: 20,770
- **Columns**: 22 features including:
  - `price`, `room_type`, `neighbourhood_group`, `availability_365`, `number_of_reviews`, etc.

---

## 🧹 Data Cleaning

- Removed rows with missing values (`dropna`)
- Removed duplicate entries (`drop_duplicates`)
- Changed data types for appropriate interpretation (e.g., `id` and `host_id` cast to `object`)

---

## 📊 Exploratory Data Analysis

### 🔍 Univariate Analysis
- **Price Distribution**: Majority of listings under \$1500; outliers heavily skew data
- **Availability**: Listings range from seasonal to year-round

### 🧠 Feature Engineering
- Created new feature: `price per bed`
- Calculated average price per neighborhood group:
  - Manhattan: \$204.15
  - Brooklyn: \$155.14
  - Queens: \$121.68
  - Staten Island: \$118.78
  - Bronx: \$107.99

### 📈 Bivariate & Multivariate Analysis
- **Price by Neighborhood & Room Type**: Manhattan shows highest prices across all room types
- **Price vs Number of Reviews**: No strong linear trend
- **Geographical Visualization**: Clusters of listings around central NYC
- **Correlation Heatmap**: Weak to moderate correlation among numerical features

---

## 📍 Key Insights

- **Manhattan is the most expensive borough**, largely due to location and demand
- **Room type significantly influences price**, with entire homes costing the most
- **Price per bed** is a useful normalization for comparing listings
- **Visual trends** highlight geographic and categorical impacts on price

---

