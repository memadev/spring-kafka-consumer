# spring-kafka-consumer
Show cases consuming messages from Apache Kafka.

First you need to run Zookeeper and Kafka(If you haven't yet).
Change to bin directory of Kafka and run zookeeper:

./zookeeper-server-start.sh ../config/zookeeper.properties

then you need to run Kafka:

./kafka-server-start.sh ../config/server.properties



Now you are able to run consumer application which consumes messages from event topic.


