# a-kafka-story-zookeeper-java-telegraf-jmx-grafana-ksql

# 🚀 Kafka ecosystem ... but step by step! kafka zookeeper kafka-streams cdc kafka-broker debezium ksql 🚀

https://github.com/coding-to-music/a-kafka-story-zookeeper-java-telegraf-jmx-grafana-ksql

From / By Florent Ramière https://github.com/framiere

https://github.com/framiere/a-kafka-story

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/a-kafka-story-zookeeper-java-telegraf-jmx-grafana-ksql.git
git push -u origin main
```

## Install Java JDK

```
java --version
```

java not found 

```
sudo apt install default-jdk
```
 
long install output... 

```
java --version
```

Output

```
openjdk 11.0.16 2022-07-19
OpenJDK Runtime Environment (build 11.0.16+8-post-Ubuntu-0ubuntu120.04)
OpenJDK 64-Bit Server VM (build 11.0.16+8-post-Ubuntu-0ubuntu120.04, mixed mode, sharing)
```

```
sudo apt install default-jre
```

Output

```
Reading package lists... Done
Building dependency tree       
Reading state information... Done
default-jre is already the newest version (2:1.11-72).
default-jre set to manually installed.
0 upgraded, 0 newly installed, 0 to remove and 35 not upgraded.
```

## Please checkout these awesome references

1. http://developer.confluent.io/
1. https://kafka-tutorials.confluent.io/

And if you want to learn another way, just follow these steps.

Make docker and maven do their thing once for all by running `./fetch.sh`

Then jump in the Kafka Story!

1. [One zookeeper, one kafka broker](step1/)
1. [One zookeeper, many kafka brokers](step2/)
1. [Java consumer, java producer](step3/)
1. [Let's add data with telegraf](step4/)
1. [Let's setup better defaults](step5/)
1. [Enter kafka stream](step6/)
1. [Capture JMX metrics](step7/)
1. [Grafana](step8/)
1. [Kafka Connect](step9/)
1. [Kafka Connect and Schema Registry](step10/)
1. [Change Data Capture](step11/)
1. [Change Data Capture and Schema Registry](step12/)
1. [Change Data Capture and Schema Registry and export to S3](step13/)
1. [Ksql](step14/)
1. [Ksql server and UI](step15/)
1. [Change Data Capture, Schema Registry and Ksql](step16/)
1. [Change Data Capture, JSON, Ksql and join](step17/)
1. [Random producer and Complex joins](step18/)
1. [Sync random producer and mysql, capture CDC diff and push it to telegraf](step19/)

Don't like Docker ? Please download Confluent platform here: https://www.confluent.io/download/

Also, please take a look at

1. https://github.com/confluentinc/cp-demo
1. https://github.com/confluentinc/demo-scene
1. https://github.com/confluentinc/examples
1. https://github.com/confluentinc/kafka-streams-examples
1. https://www.confluent.io/stream-processing-cookbook/
