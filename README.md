# Install RabbitMQ

```bash
docker run -it --rm --hostname my-rabbit --name rabbitmq -p 5672:5672 -p 15672:15672 -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=password rabbitmq:3.9-management
```
Params

```bash
-it for interactive
-d for detached
```

# Links

Based on [Cezary Walenciuk tutorial](https://www.youtube.com/watch?app=desktop&v=JjypC1LsmvY).