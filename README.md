# Start Kafka and Zookeeper services

# Open the terminal and move to the folder kafka-and-zookeper
cd <path-to>/kafka-and-zookeper/

# Start the containers
docker-compose up -d 

# Verify that both Kafka and Zookeeper container are running
# - Kafka runs on localhost:9092
# - Zookeeper runs on localhost:2181
docker ps


