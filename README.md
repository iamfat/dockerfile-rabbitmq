Docker Hub: genee/rabbitmq
===========
## RabbitMQ
```bash
docker pull genee/rabbitmq
docker run --name rabbitmq \
    -v /dev/log:/dev/log \
    -p 5672:5672 \
    -p 15672:15672 \
    -d genee/rabbitmq
```
