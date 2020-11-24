# Created by : Sagar Agrawal

# EPAI_session15

# Assignment

For this project you are given a file that contains some parking ticket violations for NYC.

(It's just a tiny extract!)

If you're wondering where I get these data sets, Kaggle is an **excellent** source of data sets in a whole variety of topics: 
https://www.kaggle.com/

You have to sign up, but it's free.

If you want the full data set, it's available here: https://www.kaggle.com/new-york-city/nyc-parking-tickets/version/2#


For this sample data set, the file is named: 
```
nyc_parking_tickets_extract.csv
```


What are your goals?

##### Goal 1
Create a lazy iterator that will return a named tuple of the data in each row. The data types should be appropriate - i.e. if the column is a date, you should be storing dates in the named tuple, if the field is an integer, then it should be stored as an integer, etc.

##### Goal 2

Calculate the number of violations by car make.

##### Note:
Try to use lazy evaluation as much as possible - it may not always be possible though! That's OK, as long as it's kept to a minimum.
