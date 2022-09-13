# RabbitMQ Test with procucer and consumer in Go Lang


## Docker run rabbitmq

docker run -d --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3-management


## Run producer
Will publish on the queue 'TestQueue'.
> go run producer.go

## Run consumer
Will consume from the queue 'TestQueue'.
> go run consumer.go

## Access RabbitMQ UI

http://localhost:15672

user: guest
pass: guest