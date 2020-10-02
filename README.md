# CalculateUniqueUsersKafka

Doodle Data Engineer Challenge

START
Ensure that Kafka and Java8+ are installed on your device

Run the following Commands to start Kafka environment:
`$ bin/zookeeper-server-start.sh config/zookeeper.properties`
`bin/kafka-server-start.sh config/server.properties`

Create a topic to store your events
`bin/kafka-topics.sh --create --topic <TOPIC-NAME> --bootstrap-server localhost:9092`
