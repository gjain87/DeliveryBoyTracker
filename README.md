# DeliveryBoyTracker
Real time location update using Kafka

Start Kafka server: bin\windows\kafka-server-start.bat config/server.properties
Start Zookeeper server:bin\windows\zookeeper-server-start.bat config/zookeeper.properties

Create topic-> bin\windows\kafka-topics.bat --create --topic topic_name --bootstrap-server localhost:9092

producer code->bin\windows\kafka-console-producer.bat --topic topic_name --bootstrap-server localhost:9092

to Consume data in console use-> bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic topic_name --from-beginning

