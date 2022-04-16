## Exploratory Data Analysis
Exploratory Data Analysis, or EDA, is an important step in any Data Analysis or Data Science project. EDA is the process of investigating the dataset to discover patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset. 
EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better.
### Importing Libraries
Importing the required libraries for Exploratory Data Analysis (pandas, numpy, matplotlib, and seaborn)
### Uploading Data Set
Uploading the Titanic.csv from existing location to the google colab
### Reading Data Set
Read the Titanic.csv dataset
### Changing Index
- Pandas default index starts from 0
- While the dataset index of the PassengerId column starts from 1
- Then we will use the index dataset of column PassengerId
### Displaying DataFrame Information
The info() method prints information about the DataFrame. The information contains the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values). Note: the info() method actually prints the info.
### Checking Missing Value
Checking whether there is a missing value (NaN) and also counting the number of the missing value in each columns in the dataset.
### Removing Duplicate Data
Remove all of duplicate data from the dataset.
