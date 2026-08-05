# Web-Server-Log-Analysis-using-Apache-Spark
Web Server Log Analysis using Apache Spark
<img width="543" height="215" alt="image" src="https://github.com/user-attachments/assets/51450597-ec49-4480-88cc-ee161302892e" />
Web Server Log Analysis using Apache Spark
Rajesh Kumar Singh
Problem Statement
Overview & background:
A U.S.-based firm intends to analyze its web server logs to study application access patterns and determine if changes are needed in its deployment strategy. Two log files in compressed (.gz) format, each corresponding to a different month, have been made available for analysis. These logs follow the Common Log Format (CLF) of Apache and contain valuable information, such as request timestamps, the requesting host, requested resources, response codes, and more. The file names are:
Access_log_Jul1995.gz
Access_log_Aug1995.gz
Since the logs are large and contain lot of information, they need to be processed and analyzed efficiently using Big Data tools. For this assignment, you will leverage Apache Spark with PySpark and SparkSQL to handle and analyze the logs. You can choose to work with either Google Colab or a local Spark setup for this task.
Data Wrangling
Before performing any analysis, you may perform appropriate data wrangling steps prepare the log data for analysis. These steps may include:
1.Parsing the log files correctly according to the Common Log Format.

2.Handling missing or malformed data.

3.Structuring the data into a format suitable for analysis and presentation.

Document each of the issues encountered during data wrangling and provide a justification for the actions taken to address them.

Analytics:
Analyze the web server logs to extract the following insights:

i.Count of total log records
−Determine the total number of log entries in the dataset.

ii.Count of unique hosts:
−Determine the number of unique hosts in the log data.

iii.Date wise unique host counts:
−For each date, identify and count the number of unique hosts accessing the web server. List the result in the date order. Print the date in dd-MMM-yyyy format.

iv.Average Requests per Host per Day:
−Calculate the average number of requests made per host for each day (day of the month). List the results in the day order.

v.Number of 404 Response Codes:
−Identify and count the number of instances where the server returned a 404 (Not Found) response code.

vi.Top 15 Endpoints with 404 Responses:
−Identify the endpoints with the most 404 errors and list the top fifteen.

vii.Top 15 Hosts with 404 Responses:
−Identify the hosts generating the most 404 errors and list the top fifteen
