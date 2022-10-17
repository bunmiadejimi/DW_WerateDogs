# Wrangle Report
## Introduction
The aim of these project was to iterate over the processes of data gathering, visual and programmatic data assessment, data clelaning towards performing informative analyses.

### Data Gathering
The twitter archive data of the @WeRateDogs account was provided by Udacity, in a .csv format. The dataframe contained 2356 observations and 17 columns, with columns including; tweet_id, dog_stage, name, etc up until August 1, 2017.

The image predictions dataset is available on the Udacity servers and was retrived programmatically using the Requests library.

Additional data were scraped from the Twitter API using the TweePy library. The information retrieved included the twitter_id, favorite_count and retweet_count.

### Data Assessment 
The datasets were assessed:
Visually, by displaying the dataset in Jupyter notebook and Excel to detect any quality and tidiness issues.
Programmatically, by employing the use of pandas functions and methods.
Various issues were detected and a total of ten quality issues and 2 tidiness issues were documented.

### Data Cleaning
Each documented issue were then addressed programmatically using a range of pandas functions.


## Conclusion
The required @WeRateDogs data were gathered, assessed and cleaned. The datasets weere pooled into one dattaframe names twitter_archive_master.csv with 1030 rows and 13 columns. The master dataset is the result of this data cleaning process, but will require further iterations to truly over all the quality and tidiness issues thay are present, since the data wrangling process id iterative.