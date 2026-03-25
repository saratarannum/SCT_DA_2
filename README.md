# SkillCraft Technology - Data Analyst Internship

## Task 02: Data Cleaning and Preparation

### 📌 Objective
Load the Global Superstore dataset and perform data cleaning and preparation using Python and Pandas.

### 🛠️ Tools & Libraries Used
- Python
- Pandas
- Jupyter Notebook

### 📂 Files
| File | Description |
|------|-------------|
| `Task02_Data_Cleaning.ipynb` | Jupyter Notebook with full code |
| `Global_Superstore_Cleaned.csv` | Cleaned dataset exported as CSV |

### 🔍 Steps Performed
1. **Loaded** the Global Superstore dataset using Pandas
2. **Explored** the data using `.shape`, `.info()`, `.describe()`
3. **Handled Missing Values**
   - Numeric columns filled with median
   - Text columns filled with "Unknown"
4. **Removed Duplicate Rows** using `drop_duplicates()`
5. **Converted Data Types**
   - `Order Date` and `Ship Date` converted from string to datetime format
6. **Exported** the cleaned data to a new CSV file

### 📊 Dataset
- **Source:** Global Superstore
- **Records:** 51,290 rows
- **Columns:** 24

### ✅ Outcome
Successfully cleaned the dataset by handling missing values, removing duplicates, and converting data types. Exported the final cleaned data as a CSV file.
