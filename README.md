# tip-prediction-spark
Tip prediction using linear regression with PySpark ML

This project utilizes PySpark's ML library to predict tips based on a linear regression model. DataFrames and pipelines are used to efficiently and concisely implement the entire workflow. Futhermore, string and categorical feature are converted to numeric and one-hot encoded features using Spark's built in functions.   

Note that this project uses the databricks package to load CSV files directly to a DataFrame. Use the following command to load PySpark in a notebook:  
PYSPARK_DRIVER_PYTHON=ipython PYSPARK_DRIVER_PYTHON_OPTS="notebook" $SPARK_HOME/bin/pyspark --packages com.databricks:spark-csv_2.10:1.3.0
