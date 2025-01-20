# Custom Kafka Producer and Consumer

## Overview
This project demonstrates a real-time streaming application using Apache Kafka. It includes a custom Kafka producer and consumer with unique functionalities:
- **Producer**: Sends custom messages to a Kafka topic.
- **Consumer**: Consumes messages from the Kafka topic and performs real-time analytics.

## Prerequisites
- Apache Kafka installed and running (Zookeeper and Kafka Broker)
- Python 3.11
- Virtual environment with dependencies installed (`kafka-python`, `dotenv`, etc.)

## Custom Scripts
### Producer
The custom Kafka producer (`kafka_producer_davidrm.py`) generates and sends personalized messages to the `buzzline` topic.

#### Command to Run the Producer:
source .venv/bin/activate
python producers/kafka_producer_davidrm.py

#### Command to run the consumer:
source .venv/bin/activate
python consumers/kafka_consumer_davidrm.py\

#### Running the Application - Start Zookeper
zookeeper-server-start.sh /path/to/zookeeper.properties

#### Start Kafka Broker
kafka-server-start.sh /path/to/server.properties
