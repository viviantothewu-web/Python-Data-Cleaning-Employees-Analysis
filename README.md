# Python-Data-Analysis-NumPy-Pandas
"NumPy and Pandas foundations: Boolean indexing, Series manipulation, and DataFrame operations."

# Employee Data Analysis & Cleaning

This project demonstrates advanced data manipulation techniques using the Pandas library to clean and analyze a corporate employee dataset.

## 🛠️ Data Engineering Techniques
* **Handling Missing Data:** Identified and isolated null values using `noNaN_df`.
* **Deduplication:** Filtered and analyzed redundant records.
* **Feature Mapping:** Implemented a custom dictionary mapping to assign "Building Locations" based on "Team" values, including custom handling for NaN entries.
* **Discretization (Binning):** Segmented salary ranges into 4 distinct bins to analyze distribution.
* **Outlier Detection:** Filtered records based on statistical thresholds (Bonus > 9.3%).
* **String Manipulation:** Used complex boolean indexing for regex-like string filtering (Start-with "S").
* **Hierarchical Indexing:** Created multi-level indexed Series objects for high-dimensional data viewing.
* **Grouped Aggregations:** Calculated multi-column averages (Salary/Bonus) grouped by Team and Gender.

## 📊 Dataset
The analysis is performed on `employees.csv`, which includes features such as First Name, Gender, Start Date, Last Login Time, Salary, Bonus %, Senior Management status, and Team.

## 🚀 Key Functions
* `top()`: A flexible function designed to extract the top $n$ entries by salary, applied across different categories (Gender) using the `apply` method.

