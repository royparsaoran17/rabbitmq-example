## Docker Rabbit MQ
docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

## RUN 
go run producer/producer.go

go run consumer/consumer.go