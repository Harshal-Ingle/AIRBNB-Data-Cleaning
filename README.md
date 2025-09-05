# Airbnb Open Data Cleaning  

## Executive Summary  
This project focuses on the crucial first step of the **data science workflow: data cleaning and preprocessing**. Using a large dataset of Airbnb listings, the goal was to transform raw, messy data into a clean, structured format suitable for analysis and modeling. The process included **handling missing values, standardizing column names, and correcting data types** to ensure data quality and reliability.  

---

## Business Problem  
Raw data is often **inconsistent, incomplete, and incorrectly formatted**, making it unsuitable for accurate analysis. For a platform like Airbnb, poor data quality can lead to unreliable insights about **pricing, host behavior, and market trends**. This project solves the challenge of preparing a **robust, clean dataset** that can support reliable business analysis and predictive modeling.  

---

## Methodology  
The data cleaning process was executed in **Python** using the **Pandas** library:  

1. **Data Ingestion**  
   - Loaded `Airbnb_Open_Data.csv` into a Pandas DataFrame.  

2. **Initial Inspection**  
   - Examined dimensions, column names, data types, and missing values.  

3. **Column Selection**  
   - Dropped irrelevant columns with excessive null values (e.g., `reviews_per_month`, `house_rules`, `license`).  

4. **Data Type Conversion**  
   - Cleaned price-related columns (`price`, `service_fee`) by removing currency symbols and commas.  
   - Converted them from object → numeric type.  

5. **Handling Missing Values**  
   - After dropping irrelevant columns, remaining nulls were removed using `df.dropna()`.  

6. **Standardization**  
   - Converted all values in `host_identity_verified` column to **uppercase** for consistency.  

---

## Skills Demonstrated  
- **Python**: Data manipulation & scripting  
- **Pandas**: Handling missing values, renaming/dropping columns, data type conversions  
- **Data Wrangling**: Identifying & resolving data quality issues  
- **File I/O**: Exporting cleaned data to CSV & Excel  
- **GitHub**: Version control & project documentation  

---

## Results  
The cleaning process produced a **refined dataset** with the following improvements:  

- Removed missing values and duplicates.  
- Standardized column formats (e.g., price → numeric).  
- Simplified dataset with only relevant columns.  
- Ensured consistent formatting for categorical features like `host_identity_verified`.  

The cleaned dataset is now **ready for Exploratory Data Analysis (EDA)** and predictive modeling.
- Exploring relationships between **price, neighborhood, and room type**.  
- Building a **predictive model** for Airbnb listing prices.  
- Visualizing **host activity and cancellation policies** across locations.  

---

## 📂 Project Structure  
