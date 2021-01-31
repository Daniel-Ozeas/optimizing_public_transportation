# Optimizing Public Transportation Project

The project consists of streaming public transit status using Kafka and the Kafka ecosystem to build a stream processing application that shows the status of trains in real-time.

The goal of the project is to give the possibility to monitor, throughout a website, trains move from station to station, like the image below.

![image](img/website1.png)

![image](img/website2.png)

![image](img/website3.png)

# About Project

The Chicago Transit Authority (CTA) has asked to develop a dashboard displaying system status for its commuters. The choice is to use Kafka and ecosystem tools like REST Proxy and Kafka Connect to accomplish this task.

The architecture is like the image below:

![image](img/architecture.png)

# About folders and files

![image](img/folders_files.png)

# How Execute scripts

### Producers
* `simulation.py`

### Consumers
* `faust -A faust_stream worker -l info`
* `python ksql.py`
* `python server.py`

