# Big Data Cloud ETL

## Background

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. <br> The goal for this assignment is to perform the ETL process completely in the cloud over 2 data sets ( I have used Video games reviews and Gift card reviews) and upload a DataFrame to the RDS instance. 

## Resources

[customer review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

- - -

## Notes

* Google Colab was used to write the ETL code and data was then copied into Jupyter Notebook to show the data frames structures.

* SQL queries in Postgres was executed to make sure the data was loaded into the respectivetables.

* **Important:** uploaded notebooks does not contain RDS password and endpoint for privacy reasons.

- - -


