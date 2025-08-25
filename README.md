## 🏡 Airbnb Data Cleaning Project
📌 Project Overview

** This project focuses on data cleaning and preprocessing of the Airbnb Open Dataset to prepare it for further analysis and visualization. The dataset originally contained messy, unstandardized data with missing values, unnecessary columns, and inconsistent formats.**

The goal was to transform the dataset into a clean, structured format suitable for exploratory data analysis (EDA) and potential dashboarding (Tableau/Power BI).

**⚙️ Tools & Libraries Used**

Python
Pandas
NumPy
Matplotlib / Seaborn (for quick checks & visualizations)
Jupyter Notebook

**🔑 Steps Performed**

Data Import & Inspection
Loaded the dataset using Pandas
Checked dataset shape, column names, and info
Column Selection & Dropping
Retained only the necessary columns (e.g., Name, Host Info, Neighbourhood, Country, Price, etc.)
Removed irrelevant or redundant columns

**Data Cleaning**

Renamed columns for readability
Removed duplicates
Handled null values
Standardized categorical values (like host identity verification, booking options, etc.)
Data Transformation
Converted data types where necessary (e.g., price, IDs, booleans)
Normalized text formatting for consistency
Final Dataset

Structured, clean, and ready for further EDA, visualization, or machine learning tasks.

**📊 Example Insights (after cleaning)**

Distribution of hosts across countries and neighbourhoods
Proportion of listings with verified hosts
Trends in booking preferences (instant bookable vs manual)
Price range distribution across different locations

📂 Airbnb-Data-Cleaning
│── Airbnb-Data_Cleaning.ipynb   # Jupyter Notebook with full process
│── Airbnb_Open_Data.csv         # Original dataset
│── Cleaned_Airbnb_Data.csv      # Final cleaned dataset (output)
│── README.md                    # Project documentation
