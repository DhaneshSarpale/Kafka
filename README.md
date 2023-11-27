
# Exploring Kafka: A Comprehensive Introduction to Basics 

This repository serves as a practical demonstration of the fundamental concepts behind Apache Kafka, showcasing a basic project with Producer and Consumer implementations. Whether you're new to Kafka or seeking a quick reference, this project provides a hands-on approach to understanding the core principles.



## Table of Content


## Getting Started

To get the project clone this repository to your local machine

```
git clone https://github.com/dhaneshsarpale/kafka.git

```
### Installtion of Kafka  
NOTE: While the demonstration has been showcased on a Windows machine, the provided code is universally applicable. For users on Ubuntu or Mac, the only variance lies in the activation process of Zookeeper and Kafka. The core functionality remains consistent across platforms. Please refer to the following section for platform-specific instructions on setting up Zookeeper and Kafka accordingly.

For windows: https://youtu.be/BwYFuhVhshI?si=9wuEbxIoob6T2w3v0  
For Ubuntu: https://www.youtube.com/watch?v=BPi2-xM-Ydc&ab_channel=DevOpsHint  
For Mac: https://www.youtube.com/watch?v=sUEIRxVbieI&ab_channel=BogdanStashchuk



## Steps to execute

### Step 1 : Initiate Kafka 

#### A.Start Zookeeper:

Kafka uses Zookeeper for distributed coordination. Start Zookeeper first.
In the Kafka directory, run the following command to start Zookeeper:
```
bin/zookeeper-server-start.sh config/zookeeper.properties
```

#### B.Start Kafka Broker:

In a new terminal, start the Kafka broker using the following command:
```
bin/kafka-server-start.sh config/server.properties
```
### Step 2 : Execute Producer and Consumer Program

##### A.Execute consumer1.ipynb
##### B.Execute producer1.ipynb
##### C.Execute producer2.ipynb


## Demo


 

https://github.com/DhaneshSarpale/Kafka/assets/140598164/b273586b-1cfd-4845-a15b-c3010eb29912

