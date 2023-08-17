# Python Kafka Producer and Consumer

This repository contains an example of how to use Python to produce and consume messages from Apache Kafka. It includes four files:
===========================================================

- docker-compose.yaml: This file defines the services used in the application, including ZooKeeper and Kafka.

- consumer.py: This file contains the code for the Kafka consumer, which listens for messages on the "messages" topic and prints them to the console.

- producer.py: This file contains the code for the Kafka producer, which sends messages to the "messages" topic at regular intervals.

- data_generator.py: This file contains the code for generating test messages that are sent between users in the system.

To run the application, simply start `Docker Compose` with the provided YAML file. Once the containers are running, you can access the Kafka server at **localhost:9092** and see the messages being produced and consumed in real-time.

**Note:** Make sure to replace the values for bootstrap_servers and group_id in the YAML file with appropriate values for your Kafka cluster.