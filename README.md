# RabbitMQ Test with procucer and consumer in Go Lang


## Docker run rabbitmq

docker run -d --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3-management


## Run producer

go run main.go

## Run consumer

go run consumer.go

## Access RabbitMQ UI

http://localhost:15672