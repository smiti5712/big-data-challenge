# Big Data Cloud ETL

## Background

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer.
<br>
<br>
The goal for this assignment was to perform ETL process completely in the cloud over 2 data sets and upload the DataFrames to RDS instance. 
I have used Video games reviews and Gift card reviews data sets.

## Resources

[customer review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

- - -

## Notes

* Google Colab was used to write the ETL code and data was then copied into Jupyter Notebook to show the data frames structures.

* SQL queries in Postgres was executed to make sure the data was loaded into the respective tables.

* **Important:** uploaded notebooks do not contain RDS password and endpoint for privacy reasons.

- - -


