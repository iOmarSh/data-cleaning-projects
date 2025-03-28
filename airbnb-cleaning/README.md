# 🏡 Airbnb Data Cleaning Project

This project focuses on cleaning a raw Airbnb dataset to prepare it for analysis or machine learning.

---

## 📁 Folder Structure

```
airbnb-cleaning/
├── airbnb_cleaning.ipynb          # Data cleaning notebook
├── data/
│   ├── airbnb_raw.csv             # Original (uncleaned) dataset
│   └── airbnb_cleaned.csv         # Final cleaned dataset
├── requirements.txt               # Python dependencies
└── README.md                      # This file
```

---

## 🚫 Raw Data Issues

The original Airbnb dataset included:
- ❌ Duplicate rows  
- ❌ Missing values (NaNs)  
- ❌ Messy or inconsistent column names  
- ❌ Prices with `$`, `,`, and spaces (as strings)  
- ❌ Numbers stored as strings  
- ❌ Useless columns (e.g. empty or irrelevant)

---

## 🧼 Cleaning Steps

In this project, I:
1. Removed duplicate entries
2. Handled missing values
3. Renamed and standardized column names
4. Cleaned price fields by removing symbols and converting to float
5. Converted numeric fields from strings to numbers
6. Dropped irrelevant or unnamed columns

---

## 📊 Tools Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy

---

## ✅ Result

The final cleaned dataset (`airbnb_cleaned.csv`) is now ready for:
- Exploratory data analysis (EDA)
- Machine learning
- Visualization dashboards

