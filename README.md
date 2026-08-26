# 🏍️ Bike Market Analysis

## 📌 Project Overview

This project focuses on **Bike Market Analysis using Web Scraping and Exploratory Data Analysis (EDA)**.

Real-world bike listing data was collected from **Flipkart** and analyzed to understand bike pricing, brand presence, engine capacity, maximum power, customer ratings, braking systems, tire types, and relationships between important features.

The final dataset contains **263 bike records and 11 analysis-ready features**.

## 🎯 Objectives

- Collect real-world bike data through web scraping.
- Extract important bike details such as price, brand, rating, engine capacity, and power.
- Clean and preprocess the scraped data.
- Standardize maximum power values into BHP.
- Perform Exploratory Data Analysis (EDA).
- Analyze pricing, performance, brands, and customer-related attributes.
- Identify relationships between important bike features.
- Generate data-driven business insights.

## 🌐 Data Source

**Website:** Flipkart  
**Category:** Non-Electric Motorcycles  
**Records:** 263  
**Features:** 11

### Features Collected

- Product Name
- Brand
- Price
- Rating
- Total Ratings
- Total Reviews
- Engine Capacity
- Maximum Power
- Front Brake
- Console Type
- Tire Type

## 🔄 Project Workflow

```text
Flipkart Bike Listings
        ↓
   Web Scraping
        ↓
   Raw Dataset
        ↓
 Data Cleaning & Preprocessing
        ↓
 Feature Engineering
        ↓
 Exploratory Data Analysis
        ↓
 Business Insights
        ↓
 Recommendations
```

## 🕷️ Web Scraping

The scraping process involved:

1. Searching bike listings on Flipkart.
2. Extracting the required bike attributes.
3. Storing the extracted information in a Pandas DataFrame.
4. Saving the collected dataset for further processing.

## 🧹 Data Cleaning & Feature Engineering

The raw scraped data contained missing values, inconsistent formats, mixed data types, and unnecessary columns.

The preprocessing included:

- Handling missing values
- Correcting data types
- Standardizing categories
- Removing unnecessary columns
- Extracting power values
- Converting power values to BHP
- Preparing an analysis-ready dataset

## 📊 Exploratory Data Analysis

The analysis covers:

- Overall bike price distribution
- Brand-wise bike model presence
- Average price by brand
- Front brake distribution
- Price variation by tire type
- Engine capacity vs. maximum power
- Correlation between numerical variables
- Price and performance relationships

## 🔍 Key Insights

- The bike market is concentrated mainly in the lower-to-mid price segment.
- **Hero** has the highest number of bike models in the analyzed dataset.
- **Harley Davidson** has the highest average bike price among the analyzed brands.
- **100–200 CC** bikes are the most commonly represented engine segment.
- Engine capacity and maximum power show a positive relationship.
- Higher-powered bikes generally have higher prices.
- Disc brakes are the most commonly listed front braking system.
- Tubeless tires are generally associated with higher median-priced bikes.

## 🛠️ Technologies & Tools

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Web Scraping**
- **Jupyter Notebook**
- **Exploratory Data Analysis (EDA)**

## 📁 Project Files

| File | Description |
|---|---|
| `webscraping.ipynb` | Notebook for collecting bike data through web scraping |
| `cleaned_data.ipynb` | Notebook for data cleaning, preprocessing, and feature engineering |
| `bike_market_analysis.pptx` | Project presentation containing analysis, visualizations, insights, and recommendations |

## ⚠️ Challenges

- Dynamic website data and changing page structures
- Inconsistent bike specification formats
- Missing values
- Different formats/units for maximum power
- Brand and category standardization
- Filtering out electric-bike-specific records

## 📌 Conclusion

The project demonstrates an end-to-end data analytics workflow:

**Real-world data → Web Scraping → Data Cleaning → Feature Engineering → EDA → Business Insights**

The analysis successfully transformed **263 scraped bike listings into an analysis-ready dataset with 11 features** and identified useful relationships between pricing, engine capacity, power, brands, and bike features.

## 👤 Project Contributors

**Dasari Siva Krishna**  
MSc | Data Science Trainee  
Skills: Python, SQL, Power BI, Excel, Web Scraping

**Kolluru Hemanth**  
BTech (AI & ML) | Data Science Trainee  
Skills: Python, SQL, Power BI, Excel, Web Scraping
