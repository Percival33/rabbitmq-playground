# RabbitMQ playground

```bash
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.13-management
```

```bash
python -m pip install pika --upgrade
```