# hands-on-pyspark
Hands-on Introduction to Apache Spark using pySpark


## Step 1

Create an account [here](https://community.cloud.databricks.com/login.html) to use the Databricks Community Edition.

Databricks is a Unified Analytics Platform on top of Apache Spark. Databricks incorporates an integrated workspace for exploration and visualization so users can learn, work, and collaborate in a single, easy to use environment.


## Step 2

![ScreenShot](https://github.com/codeworks-data/hands-on-pyspark/blob/master/databricks/welcome_db.png)


Create a blank notebook :
- name : hands-on-pySpark-{FIRSTNAME}
- Default language : Python



## Step 2

- In the top left, click `File`then `Upload Data`
- Upload `flight_delays_train.csv` file 
- Copy the code in the right section : `df = spark.read.format("csv").load("dbfs:/FileStore/shared_uploads/{EMAIL_ADDRESS}/flight_delays_train.csv")`



