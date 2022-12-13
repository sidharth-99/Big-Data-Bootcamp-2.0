Pandas Assignment 

Q1. How do you load a CSV file into a Pandas DataFrame?

Ans: 
```
import pandas as pd
df=p.read_csv("File Path")

```

Q2. How do you check the data type of a column in a Pandas DataFrame?

Ans: 
```
import pandas as pd
df=p.read_csv("File Path")
df.dtypes
```

Q3. How do you select rows from a Pandas DataFrame based on a condition?

Ans:
```
df.loc[df['column_name'] == some_value]
```

Q4. How do you rename columns in a Pandas DataFrame?

Ans: We can remname the columns using the keyword "rename"
```
df.rename(columns = {'column_name1':'column_name2'}, inplace = True)
```

Q5. How do you drop columns in a Pandas DataFrame?

Ans: We can drop columns with the command del
```
del df["column name"]
```


Q6. How do you find the unique values in a column of a Pandas DataFrame?

Ans:  
```
df["column name"].unique()
```

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?

Ans:
```
df.isnull().sum()

```

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?

Ans:
```
df.fillna(0)
```

Q9. How do you concatenate two Pandas DataFrames?

Ans:

```
vertical_stack = pd.concat([df1, df2], axis=0)
horizontal_stack = pd.concat([df1, df2, axis=1)
```


Q10. How do you merge two Pandas DataFrames on a specific column?

Ans:
```
df= pd.merge(df1, df2 ,how='inner',left_on = 'Id', right_on = 'Id')
```

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?

Ans:
```
df2.groupby(["Column Name"]).sum()
```

Q12. How do you pivot a Pandas DataFrame?

Ans: We can pivot datarame with Pands using the pivot keyword.
```
df.pivot(index='', columns='', values='')
```

Q13. How do you change the data type of a column in a Pandas DataFrame?

Ans: To change the data type of a column in a Pandas DataFrame, you can use the astype method
```
df['col'] = df['col'].astype('float64')
```

Q14. How do you sort a Pandas DataFrame by a specific column?

Ans:
```
df = df.sort_values('column name')
```

Q15. How do you create a copy of a Pandas DataFrame?

Ans:
To create a copy of a Pandas DataFrame, you can use the copy method. This method returns a new DataFrame object that contains the same data as the original DataFrame. For example, if you have a DataFrame df, you can create a copy of that DataFrame like this:

```
df_copy = df.copy()
```
This will create a new DataFrame object called df_copy that contains the same data as the original df DataFrame. Any changes you make to df_copy will not affect the original df DataFrame.

It's important to note that the copy method only creates a shallow copy of the DataFrame, which means that the new DataFrame will still reference the underlying data in the original DataFrame. If you modify the data in the original DataFrame, those changes will also be reflected in the copied DataFrame. If you want to create a deep copy of the DataFrame, where the new DataFrame has its own copy of the data, you can use the copy(deep=True) method. For example:

```
df_copy = df.copy(deep=True)
```
This will create a new DataFrame object that contains its own copy of the data from the original DataFrame, and any changes you make to the data in the copied DataFrame will not affect the data in the original DataFrame.

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

Ans: We can use the help of operators like '&' for "and" statements and '|' for 'or' statements.

```
df = df.loc[(df['col1'] > 0) & (df['col2'] == 'abc') | (df['col3'] < 100)]
```

Q17. How do you calculate the mean of a column in a Pandas DataFrame?

Ans: We can use the help of mean function in Pandas.
```
df.mean(axis = 0)
```

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?

Ans: We can use the help of std function.

```
df.std()
```

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?

Ans:
To calculate the correlation between two columns in a Pandas DataFrame, you can use the .corr() method. This method calculates the Pearson correlation coefficient by default, which measures the linear relationship between two columns.

```
corr = df['A'].corr(df['B'])
```

Q20. How do you select specific columns in a DataFrame using their labels?

Ans: We can use the functions 'loc' or [] method.

Q21. How do you select specific rows in a DataFrame using their indexes?


Q22. How do you sort a DataFrame by a specific column?

Q23. How do you create a new column in a DataFrame based on the values of another column?

Q24. How do you remove duplicates from a DataFrame?

Q25. What is the difference between .loc and .iloc in Pandas?
