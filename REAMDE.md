# Kafka active-active multi cluster deployment - experiment

<https://www.altoros.com/blog/multi-cluster-deployment-options-for-apache-kafka-pros-and-cons/>


## TODO:

- [ ] Setup 2 cluster of kafka (each has 2 network interfaces)


## Note:

- The Pypi package `kafka-python==2.0.2` has some bug, use [confluent-kafka-python](https://github.com/confluentinc/confluent-kafka-python) instead
- Python code are from <https://towardsdatascience.com/kafka-python-explained-in-10-lines-of-code-800e3e07dad1>