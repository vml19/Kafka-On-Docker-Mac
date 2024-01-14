# Run Kafka using Docker on MacBook

## Installation

Clone Kafka docker compose
```sh
clone https://github.com/conduktor/kafka-stack-docker-compose.git
cd kafka-stack-docker-compose
```
<img width="1012" alt="Screenshot 2024-01-14 at 11 49 33" src="https://github.com/vml19/Kafka-On-Docker-Mac/assets/50040501/6ddc64aa-5511-47d1-875e-3be7612ec8a6">

Start Kafka single cluster
```sh
docker-compose -f zk-single-kafka-single.yml up -d
```
Verify that the Kafka single cluster is up and running
```sh
docker-compose -f zk-single-kafka-single.yml ps
```
<img width="1672" alt="Screenshot 2024-01-14 at 12 13 15" src="https://github.com/vml19/Kafka-On-Docker-Mac/assets/50040501/01dd0852-dbf2-4217-b20e-d233006d85f7">
