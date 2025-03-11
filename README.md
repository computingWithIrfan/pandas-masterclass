# pandas-masterclass 🐼  

<p align ="center">
  <img src="img/pandas.jpg" width="450" height="300">
</p>



## Overview  
This repository is a comprehensive guide to using **Pandas**, the powerful Python library for data manipulation and analysis. It contains step-by-step Jupyter notebooks that cover everything from installation to advanced data operations.  

## Notebooks Included  
### 1. **Pandas Basics - Installation, DataFrame Creation & Operations**  
   - Installing Pandas  
   - Creating Series and DataFrames  
   - Loading data from CSV, Excel, and JSON  
   - Viewing and inspecting data (`head()`, `info()`, `describe()`)  
   - Basic DataFrame operations (`adding/removing columns`, `modifying values`)  
   - Sorting and ordering data  

### 2. **Accessing, Filtering & Handling Missing Data**  
   - Selecting data (`loc[]` and `iloc[]`)  
   - Filtering rows based on conditions  
   - Using Boolean indexing  
   - Handling missing data:  
     - Checking for missing values (`isnull()`, `notnull()`)  
     - Filling missing values (`fillna()`)  
     - Dropping missing values (`dropna()`)  
     - Replacing missing values (`replace()`)  

### 3. **Merging, Grouping & Pivoting Data**  
   - Merging and joining datasets:  
     - `merge()` for relational data joins  
     - `concat()` for stacking DataFrames  
     - `join()` for merging on indexes  
   - Grouping and aggregating data:  
     - `groupby()` for summarizing data  
     - Applying aggregation functions (`sum()`, `mean()`, `count()`, etc.)  
   - Pivot tables:  
     - Creating pivot tables with `pivot_table()`  
     - Reshaping data with `melt()` and `stack()/unstack()`  

## Installation & Setup  
To run these notebooks on your local machine:  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/pandas-complete-guide.git
   cd pandas-complete-guide
