# Apache-kafka-client-for-client
Python client for the Apache Kafka distributed stream processing system. kafka-python is designed to function 
much like the official java client, with a sprinkling of pythonic interfaces.
> Background Information about Apache kafka

Apache Kafka is an open-source stream-processing software platform developed by the Apache Software Foundation, written in Scala and Java. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds. Its storage layer is essentially a massively scalable pub/sub message queue architected as a distributed transaction log,making it highly valuable for enterprise infrastructures to process streaming data. Additionally, Kafka connects to external systems (for data import/export) via Kafka Connect and provides Kafka Streams, a Java stream processing library.

Think of it is a big commit log where data is stored in sequence as it happens. The users of this log can just access and use it as per their requirement.
Kafka Use Cases

Uses of Kafka are multiple. Here are a few use-cases that could help you to figure out its usage.

    ### Activity Monitoring:- 
    Kafka can be used for activity monitoring. The activity could belong to a website or physical sensors and devices. Producers can publish raw data from data sources that later can be used to find trends and pattern.
    ### Messaging:- 
    Kafka can be used as a message broker among services. If you are implementing a microservice architecture, you can have a microservice as a producer and another as a consumer. For instance, you have a microservice that is responsible to create new accounts and other for sending email to users about account creation.
    ### Log Aggregation:- 
    You can use Kafka to collect logs from different systems and store in a centralized system for further processing.
    ### ETL:- 
    Kafka has a feature of almost real-time streaming thus you can come up with an ETL based on your need.
    ### Database:- 
    Based on things I mentioned above, you may say that Kafka also acts as a database. Not a typical databases that have a feature of querying the data as per need, what I meant that you can keep data in Kafka as long as you want without consuming it.

> Kafka Concepts
.
<img align="left" alt="Visual Studio Code" width="200px" src="https://miro.medium.com/max/622/1*48ck-bvatKzEpVapVa4Mag.png" />

