 # Aim: Study of Pandas Library

 # Theory: 
Introduction to Pandas
Pandas (Panel Data) is a powerful Python library used for:

Handling structured and tabular data

Data manipulation and preprocessing

Statistical analysis

Data filtering and transformation

It provides two main data structures:

Series → One-dimensional labeled array

DataFrame → Two-dimensional labeled data structure (tabular format)

# Commands Used:
1. Importing Pandas - import pandas as pd
2. Creating a Series - s = pd.Series([10,20,30,40])
3. Creating a DataFrame - data = {
 "Name":["A","B","C"],
 "Marks":[85,90,78]
}
DF = pd.DataFrame(data)
4. DF.shape - Returns tuple (rows, columns)
5. DF.ndim - Returns number of dimensions
6. DF.size - Returns total number of elements
7. DF.columns - Returns list of column names
8. DF.dtypes - Returns datatype of each column
9.  DF["Name"] - Accessing a Column
10. DF.loc[0,"Name"] - Accessing Data Using loc 
11. DF.iloc[2,1] - Accessing Data Using iloc -
12.DF["Grade"] - ["First Class", "Distinction", "Second Class"] -  Adding a New Column
13. DF.drop() - Removes specified column
14. .mean() - Calculates average value of the column
15. .min() - Returns minimum value in the column
16. .max() - Returns maximum value in the column
17. DF[DF["Marks"] > 80] - Filters rows based on condition.
