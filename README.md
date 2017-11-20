# Cabs-vs-Uber

This is an repository where you can find the data and the notebook that I used to check whether Uber is beating the traditional cab companies in NYC. The results are summerized in this [post](https://gt987.github.io/data%20lens/transportation/Cabs-vs-Uber/).

# Data

The data is provided by TLC and can be found [here](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml).
The total amount of data is huge! so huge that is does not fit on my computer. Fortunately a large part of it can be already found in [BigQuery](https://cloud.google.com/bigquery/public-data/nyc-tlc-trips), and can be assessed via SQL queries.

The 2017 data is not there, so I downloaded from TLC. Also there is an error in how BigQuesry retrive the FHV data in June 2015, which I've fixed by looking directly at the TLC data. 

# Notebook

In the notebook you can find the code to download the data from TLC and the code that I used to make to plot for the blog post. This is an uncommented notebook, but everything is straightforward. 
