# Run Kafka using Docker on MacBook

## Installation

Clone Kafka docker compose
```sh
clone https://github.com/conduktor/kafka-stack-docker-compose.git
cd kafka-stack-docker-compose
```

Start Kafka single cluster
```sh
docker-compose -f zk-single-kafka-single.yml up -d
```
Verify that the Kafka single cluster is up and running
```sh
docker-compose -f zk-single-kafka-single.yml ps
```