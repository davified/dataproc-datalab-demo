# Dataproc Datalab Demo with NYC Taxi Data

This notebook demonstrates how to:
1) load data from bigquery
2) transform data using pyspark
3) train and evaluate model using pyspark
4) save and load model to a GCP bucket 

This notebook will not work out of the box (it's purely for reference). It requires that you:
1) create a gcp dataproc cluster 
2) create a dataset (named taxi_demo) and a table (named taxi_data) in gcp big query 
3) create a temporary gcp bucket
