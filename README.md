# Experiment-11
# Aim
To Create Dataset and Load Dataset in pandas library.
# Theory
1. Dataset- A dataset is a collection of data organized in a structured format such as rows and columns.In pandas, datasets are represented using a DataFrame, which is a 2-dimensional tabular data structure (like an Excel sheet).
2. Creating Dataset- Creating a dataset means manually defining data inside Python and converting it into a DataFrame.
3. Loading a Dataset- Loading a dataset means importing data from external sources into pandas.
4. Import pandas- This line imports the pandas library.Pandas is used for data handling and analysis.
5. Then a dataset is created through dictionary,list etc.
6. df = pd.DataFrame(data)-Converts the dictionary into a dataframe and df is now a table.
7. df.to_csv("students.csv", index=False)-Saves the dataframe into a file named students.csv.
8. df.shape- It returns the dimensions of the dataframe in the form of (rows,columns).
9. df.size- It returns the total number of elements (values) in the DataFrame.(size=rows*columns).
10. df.info() is a function used to get a summary of a dataframe.It gives quick information about the structure of the dataset.It gives Number of entries (rows), column names, non-null values data types and memory usage.
11. df.describe() is used to generate statistical summary of a dataframe.It mainly works on numerical columns.
    count- It gives number of non-null values.
    mean- It gives average value.
    std-It gives standard deviation (spread of data).
    min-It gives minimum value.
    25%-It gives first quartile.
    50%-It gives median.
    75%-It gives third quartile.
    max-It gives maximum value.
12. import numpy as np-It imports NumPy library which is used for numerical operations (arrays, math functions).
13. df = pd.read_csv('/Cars93.csv')- read_csv() is used to load a dataset from a CSV file and '/Cars93.csv' is the file path.
14. df.head-It is used to display the first few rows of a dataframe.By default, it shows first 5 rows.
15. df.tail-It is used to display the last few rows of a dataframe.By default, it shows last 5 rows.
16. df.sample(5) is used to select random rows from a dataframe.It returns 5 random rows from the dataset.
17. df.columns is used to get the names of all columns in a dataframe.
18. df.isnull().sum()-It is used to check missing (null) values in each column of a datarfame.
19. df.duplicated().sum()-It is used to find the number of duplicate rows in a dataframe.
20. df.nunique() is used to count the number of unique (distinct) values in each column of a dataframe.
# Conclusion
Pandas in python enables easy creation and loading of datasets into datadframes, making data handling and analysis simple and efficient.
