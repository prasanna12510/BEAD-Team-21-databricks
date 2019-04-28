# BEAD-Team-21-databricks
Databricks environment code repository Pyspark<br/>

The above repository consists of Ingestion script to batch pull in generated yelp and amazon review data and ETL preprocessing using SparkSQL to convert file to parquet in databricks HDFS scripts using PySpark, DeeplearningModelTraining scipt for deep learning techniques LSTM, CNN using keras and tensorflow with PySpark for fake vs non fake classification. The Sentiment mining script uses Sentiwordnet with Perceptron tagger and pos tagger for sentiment polarity score of the reviews in an unsupervised manner. The fake review detection script deals with various ML models built using naive bayes, decision tree, random forest and gradient boost algorithms for classification. The fake review airflow script uses directed acyclic graph script to pull data from webhose api and store it in Big query table. Lastly, the visualization script shows fake vs non fake review aggregations with regards to extracted features like sentiment score and product features like product id.

Submitted by Team 21<br/>
![Image](https://github.com/sabrish89/BEAD-Team-21-databricks/blob/master/Team_21_roster.PNG)<br/>
