# Customer-Transaction-EDA

The dataset is downloaded from Kaggle. It is related to Customer transactions. Exploratory Data Analysis has been performed on this dataset. 
The dataset has been read in jupyter notebook and stored in a dataframe. There are nine series in this dataframe, viz., Customer ID, Name, Surname,
Gender, Birthdate, Transaction Amount, Date, Merchant Name and Category. 

The following observations were made while analyzing the data and then underlying problems were solved, followed by some meaningful insights:



1 - Firstly, it was observed that there were not any outliers in the data.



2 - There were many null values in one of the series though, i.e., Gender, which were removed by randomly allocating 'Male' value and 'Female' value
to the null cells in this series. This was done due to the ratio of Female to male when null values were not removed. It was observed that the numbe
of females were slightly more than males. This ratio remained almost same even after applying random function to this series.



3 - Then, the range of 'Transaction Amount' was observed. The graph came out to be a right skewed distribution, suggesting that extremely higher transaction
amounts were fewer.



4 - It was observed that slightly more proportion of females (50.6%) accounted for the 'Transaction Amount' as compared to males (49.4%).



5 - Three additional series were added to the dataframe - 'Age', 'Age Range' and 'Month'.


6 - Customers within 20 to 30 years spent the most.


7 - Customers spent the most on 'Travel' and the least on 'Restaurant'.



8 - Lastly, the time of the year did not matter much and had almost no impact on the 'Transaction Amount'.
