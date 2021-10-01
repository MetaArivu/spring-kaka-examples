 # Changes in server.properties for ssl implementation

## 1. listeners=PLAINTEXT://:9092,SSL://:9093
## 2. advertised.listeners=PLAINTEXT://localhost:9092,SSL://localhost:9093
## 3. ssl.keystore.location=/kafka_2.11-2.4.1/ssl/kafka.server.keystore.jks
## 4. ssl.keystore.password=password
## 5. ssl.key.password=password
## 6. ssl.truststore.location=/kafka_2.11-2.4.1/ssl/kafka.server.truststore.jks
## 7. ssl.truststore.password=password
## 8. ssl.enabled.protocols=TLSv1.2,TLSv1.1,TLSv1