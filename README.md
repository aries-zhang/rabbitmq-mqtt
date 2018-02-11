# RabbitMQ-MQTT

This is a rabbitmq image with mqtt and management plugin enabled. Use the following command to have fun with.

```docker run -d --name rabbitmq -p 15672:15672 -p 5672:5672 -p 1833:1833 -p 8833:8833  -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=password 9c796d87f6b5```