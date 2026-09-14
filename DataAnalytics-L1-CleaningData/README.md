# Level 1 - Task 3: Cleaning Data

## 🎯 Project Objective
Demonstrate professional-level data cleaning skills by taking a deliberately messy dataset and systematically transforming it into a clean, structured, and analysis-ready dataset.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

## 📋 Key Steps & Data Cleaning Pipeline
1. **Data Inspection & Profiling:**
   - Evaluated data structure (`info()`, `describe()`), data types, and memory usage.
   - Identified missing values, duplicate entries, and inconsistent column headers.

2. **Handling Missing & Irregular Values:**
   - Imputed or dropped missing records appropriately based on feature distributions.
   - Handled anomalies, special characters, and formatting irregularities.

3. **Data Type Casting & Normalization:**
   - Converted date strings to proper `datetime` objects.
   - Standardized categorical text values (handling capitalization, extra whitespaces).
   - Cleaned currency/numeric columns with string symbols to float/integer.

4. **Outlier Detection & Handling:**
   - Detected unrealistic numerical values and outliers using statistical bounds.

5. **Exporting Cleaned Data:**
   - Saved and verified the cleaned dataset ready for downstream analysis.
