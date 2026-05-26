# AI & ML Internship Task 2

## Title
Data Cleaning & Missing Value Handling

---

## Objective

The objective of this task is to understand the importance of data cleaning and missing value handling in machine learning preprocessing.

This task focuses on:
- Identifying missing values
- Visualizing missing data
- Handling missing values using imputation techniques
- Detecting and removing outliers
- Saving cleaned dataset

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## Dataset Used

Housing Prices Dataset

Dataset contains housing-related information such as:
- Sale Price
- Lot Area
- Street
- Neighborhood
- Building Type
- Garage Information
- Basement Information

---

## Libraries Used

### 1. Pandas
Used for:
- Loading dataset
- Data manipulation
- Data cleaning

### 2. NumPy
Used for numerical operations.

### 3. Matplotlib
Used for data visualization.

### 4. Seaborn
Used for heatmap and boxplot visualization.

### 5. SimpleImputer
Used for handling missing values automatically.

---

## Tasks Performed

### 1. Uploaded Dataset
Uploaded housing dataset CSV file in Google Colab.

### 2. Loaded Dataset
Used Pandas to load dataset into dataframe.

### 3. Explored Dataset
Used:
- head()
- shape
- info()

to understand dataset structure.

### 4. Checked Missing Values
Used:
```python
df.isnull().sum()
```

to identify missing values in columns.

### 5. Visualized Missing Values
Used heatmap visualization to identify missing data patterns.

### 6. Identified Numerical and Categorical Columns

Separated:
- Numerical columns
- Categorical columns

using data types.

### 7. Handled Missing Values

#### Numerical Columns
Used Median Imputation because housing data contains outliers.

#### Categorical Columns
Used Mode Imputation using most frequent values.

### 8. Detected Outliers
Used boxplot visualization for outlier detection.

### 9. Removed Outliers
Used IQR (Interquartile Range) method to remove extreme values.

### 10. Saved Cleaned Dataset
Saved cleaned dataset as:

```text
cleaned_housing_data.csv
```

---

## Missing Value Handling Techniques Used

### Median Imputation
Used for numerical columns because:
- Robust against outliers
- Better for skewed data

### Mode Imputation
Used for categorical columns because:
- Fills missing values using most repeated category

---

## Outlier Detection Method

Used IQR Method:

- Q1 = 25th percentile
- Q3 = 75th percentile
- IQR = Q3 - Q1

Outliers outside acceptable range were removed.

---

## Observations

- Dataset contained missing values in multiple columns.
- Heatmap helped visualize missing data.
- Numerical and categorical columns were identified successfully.
- Missing values were handled properly.
- Outliers were detected and removed.
- Dataset became clean and ready for machine learning preprocessing.

---

## Final Outcome

Successfully performed:
- Data cleaning
- Missing value handling
- Outlier detection
- Outlier removal
- Dataset preprocessing

The cleaned dataset is now suitable for machine learning tasks.

---

## Files Included

- Housing_Data_Cleaning.ipynb
- train (1).csv
- cleaned_housing_data.csv
- README.md

---

## Author

Arya Chighare

