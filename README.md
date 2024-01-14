# Run Kafka using Docker on MacBook

## Installation

Clone Kafka docker compose
```sh
clone https://github.com/conduktor/kafka-stack-docker-compose.git
cd kafka-stack-docker-compose
```
<img width="1672" alt="Screenshot 2024-01-14 at 12 17 07" src="https://github.com/vml19/Kafka-On-Docker-Mac/assets/50040501/c78b3f33-12d1-40d7-a270-e221af0eb1db">

Start Kafka single cluster
```sh
docker-compose -f zk-single-kafka-single.yml up -d
```
Verify that the Kafka single cluster is up and running
```sh
docker-compose -f zk-single-kafka-single.yml ps
```
<img width="1672" alt="Screenshot 2024-01-14 at 12 16 46" src="https://github.com/vml19/Kafka-On-Docker-Mac/assets/50040501/30ed304b-d2ac-4ae0-bd58-0846b47d1e25">

### References
1. https://www.conduktor.io/kafka/how-to-start-kafka-using-docker/
