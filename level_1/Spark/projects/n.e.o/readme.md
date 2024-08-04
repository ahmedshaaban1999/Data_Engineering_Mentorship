# NASA Nearest Earth Objects
## Project Overview:
NASA provide free access to a dataset that contains the nearest objects to Earth. You need to load the dataset into an Apache Hive table, then connect to it using Apache Spark and extract some insights to be saved into HDFS. You are free to use any Apache Spark API.

## Resources:
a single csv file containing the N.E.O dataset from 1910 to 2024. [source](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)

## Requirements:
1. Load the file into HDFS.
2. Create an external Hive table on the file.
3. Read the data using Spark.
4. Extract the neo_ids and names top 10 hazardous objects based on the momentum equation (momentum = mass * velocity). Calculate the mass using the minimum diameter and a density of 3 gm/cm3.
5. Save the results in a file named "top10_hazardous.txt" under a folder named "NASA" under the root directory. the file should have the neo_id and name of each of the top 10 objects separted with " - ".

## Key Deliverables:
-	Apache Spark code.
