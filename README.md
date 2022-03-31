# Kafka Python

> You will learn how to create Kafka producer and Consumer in python.

1. Install `kafka-python` we will use `KafkaProducer` and `KafkaConsumer`

```commandline
pip3 install kafka-python
```

2. Run `01-start-zookeeper.sh` start zookeeper server
3. Run `02-start-kafka.sh` start kafka server
4. Run producer.py
5. Run consumer.py

![](https://i.imgur.com/f0BJxU1.png)

This is it. We have created our first Kafka consumer in python. We can see this consumer has read messages from the topic and printed it on a console.

## Git push script

```
git add . && git commit -m 'new app' && git push
```
