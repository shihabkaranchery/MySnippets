# Pandas study Nots

* to read a csv file

`
import pandas as pd
`

`
df = pd.read('filename.csv')
`
# Pandas
* Pandas is derived from the word Panel Data – an Econometrics from Multidimensional data
* In 2008, developer Wes McKinney started developing pandas when in need of high performance, flexible tool for analysis of data.

# Series
* Homogeneous data
* Size Immutable
* Values of Data Mutable
* s = pd.Series(np.random.randn(2)) -> s.size - returns the size of the object
* s.values -> Returns the actual data in the series as an array.
* s.head() returns the first n row, s.head(2)
* tail() returns the last n rows, The default number of elements to display is five, but you may pass a custom number.



# pandas.Series
* pandas.Series( data, index, dtype, copy)
 data - data takes various forms like ndarray, list, constants

# Panel
* Panel is a three-dimensional data structure with heterogeneous data
* Size Mutable
* Data Mutable

# Dataframe
* DataFrame is a two-dimensional array with heterogeneous data
* tabular data structure, rows and coloums
* df.shape -> return (rows, column)
* rows, colum = ds.shape
* df.head() -> return initial few rows of the sheet
* df.head(2) -> retunr only first two rows
* df.tail() -> last five rown
* df[2:5] -> slicing supports
* df.columns -> return columns
* df.column_name -> return the column detaisl
* df['collumn_name] -> return the column
* columns is the pandas series data type
* df[['column1']['column2']]
* df['col_name'].max() - return the maximum number
* df['col_nmae].min(), mean()-> for average
* df.describe() -> return statistics of the columns
* df[['column1']['column2']][df.<coloumn>==<confition>] - select with condition
* https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.html

* df.set_index('day') - return new data frame
* df.set_index('day', inplace=True) - alter the existing df
* df.loc[<index>] - return the perticular row of this index
* df.reset_index(inplace=True) - revert the index
* df.values -> Returns the actual data in the DataFrame as an NDarray.


