# 🐍 Data Analysis with Python

## 📌 Introduction

This repository contains basic data analysis operations using popular Python libraries: **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. It is aimed at beginners looking to understand how to use these tools for exploring and analyzing datasets.

---

## 📚 Libraries Used

### 🐼 Pandas  
![Pandas](https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg)

### 📊 NumPy  
![NumPy](https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg)

### 📈 Matplotlib  
![Matplotlib](https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg)

### 🌊 Seaborn  
![Seaborn](https://seaborn.pydata.org/_static/logo-wide-lightbg.svg)

---

## 🔍 What’s Covered

### 📌 Pandas
1. Reading a CSV file using `read_csv()`
2. Viewing the first few rows with `head()`
3. Getting basic info with `info()` and `describe()`
4. Displaying data types with `dtypes`
5. Checking null values with `isnull()` and `isnull().any()`
6. get total count of null values with `isnull().sum()`
7. Fill null value using the mean value with `fillna(df.colName.mean())`
8. Fill null values using upper cell and lower cell value with `fillna(method='ffill', inplace=True)`, `ffill()` and `bfill()`
9. Print all columns name with `df.columns`
10. Rename column name with `df.rename(columns={'before':'after'})`
11. Change data type with `astype()`
12. Apply custom function to a specific column with `apply()`
13. Grouping and aggregating with `groupby()`, `count()`, `mean()` and `sum()`
14. Apply multiple aggregate functions with `agg(['mean', 'max', 'min'])`
15.  Joining and Merging with `merge(df1, df2, on='key', how='inner')`, `merge(df1, df2, on='key', how='outer')`, `merge(df1, df2, on='key', how='left')` and `merge(df1, df2, on='key', how='right')`
16. Data selection using `loc[]` and `iloc[]`
17. Filtering and sorting data

### ➕ NumPy
1. Creating arrays
2. Array slicing and indexing
3. Basic arithmetic operations
4. Useful functions like `np.mean()`, `np.std()`, etc.

### 📊 Matplotlib
1. Plotting line graphs
2. Bar charts
3. Histograms
4. Customizing plots (title, labels, legend)

### 🌊 Seaborn
1. Creating beautiful statistical plots
2. Plot types: `sns.histplot`, `sns.boxplot`, `sns.scatterplot`
3. Styling and themes

---

## 📁 Folder Structure

```text
Data-Analysis-with-Python/
│
├── pandas               # Contains CSV or other datasets
├── numpy          # Jupyter notebooks with code and analysis
├── matplotlib
├── seaborn
├── insurance.csv
├── tips.csv             # Screenshots or output images
├── README.md           # This file
└── requirements.txt    # Python dependencies


---

## ✅ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Data-Analysis-with-Python.git
   cd Data-Analysis-with-Python
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks:

   ```bash
   jupyter notebook
   ```

---

## ✍️ Author

* **Your Name** – [Md. Jahidul Alam](https://github.com/jahidsagar)

---

```

---

### ✅ Next Steps:

- Replace `yourusername` and `Your Name` with your actual GitHub username and name.
- If you're storing images or outputs, update the `images/` folder section with actual examples.
- Keep the README updated as your project grows.

Let me know if you want help generating a `requirements.txt` file or adding example images!
```
