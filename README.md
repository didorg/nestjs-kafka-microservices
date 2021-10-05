# nestjs-kafka-tutorial

## How to run Kafka locally

You need to have docker installed and run  
```
docker-compose up -d
```

It will serve a kafka ui dashboard in port 8080 `http://localhost:8080/`  

## Running the producer

The producer code is in the producer folder and serves a small scaffold that contains the configuration of the producer.

Inside the producer folder run `npm install`  
Run the producer in dev mode `npm run start:dev`

## Running the consumer

The consumer code is in the consumer folder and serves a small scaffold that contains the configuration of the consumer.

Inside the consumer folder run `npm install`   
Run the consumer in dev mode `npm run start:dev`  

## Test the App  
`GET` to `http://localhost:3000/kafka-test` to emit a JSON message to the topic.  

### request/response approach  
`GET` to `http://localhost:3000/kafka-test-with-response`

Reference [Article](https://makinhs.medium.com/a-beginners-introduction-to-kafka-with-typescript-using-nestjs-7c92fe78f638)
