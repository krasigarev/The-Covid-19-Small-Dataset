# The Covid-19 Small Dataset

## The commands that we used in this project :

- pd.read_csv - To import the CSV file in Jupyter notebook
- df.count() - It counts the no. of non-null values of each column.
- df.isnull().sum() - It detects the missing values from the dataframe.
- sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
- plt.show() - To show the plot.
- df.groupby(‘Col_name’) - To form groups of all unique values of the column.
- df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.
- df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.

## Tasks:

- Show the number of Confirmed, Deaths and Recovered cases in each Region.
- Remove all the records where the Confirmed Cases is Less Than 10.
- In which Region, maximum number of Confirmed cases were recorded?
- In which Region, minimum number of Deaths cases were recorded?
- How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020?
- Sort the entire data wrt No. of Confirmed cases in ascending order.
- Sort the entire data wrt No. of Recovered cases in descending order.
