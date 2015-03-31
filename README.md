Docker Hub: genee/rabbitmq
===========
## RabbitMQ
```bash
docker pull genee/rabbitmq
docker run --name rabbitmq \
    -v /dev/log:/dev/log \
    -v /var/lib/rabbitmq/:/var/lib/rabbitmq/ \
    -p 5672:5672 \
    -p 15672:15672 \
    -d genee/rabbitmq
```
