# Logs reader
## Project Overview:
Assume you have a folder where log files are created by some software tool. This tool create a log file and writes logs in it in real time. The tool creates a new file every hour to write the logs of that hour into. This log files creation and rotation technique is used by many tools.

Write an Apache Kafka producer to read the current log file, and send each line as a separte message to a topic named "logs". The current log file will be named "apache.log" and will be renamed when rotated into "apache_<YYYMMDD_HH>.log" where <YYYMMDD_HH> is the timedate pattern of the logged data. You can use any Apache Kafka API.

## Resources:
a sample log file [source](https://github.com/logpai/loghub/blob/master/Apache/Apache_2k.log)

## Requirements:
1. Write producer to listen for any new lines added to the current log file and send them immediately to a single node kafka cluster under a topic named "logs"

## Key Deliverables:
-	producer code
