# Key Value DB

### RabbitMQ&#x20;

"RabbitMQ is an open-source message-broker software that originally implemented the Advanced Message Queuing Protocol and has since been extended with a plug-in architecture to support Streaming Text Oriented Messaging Protocol, MQ Telemetry Transport, and other protocols."

* [Producer broker, consumer - a tutorial on what is RMQ](https://www.cloudamqp.com/blog/2015-05-18-part1-rabbitmq-for-beginners-what-is-rabbitmq.html)
* [Part2.3](https://www.cloudamqp.com/blog/2015-05-21-part2-3-rabbitmq-for-beginners\_example-and-sample-code-python.html) - python code
* [Part 3](https://www.cloudamqp.com/blog/2015-05-27-part3-rabbitmq-for-beginners\_the-management-interface.html) -  managing
* [Part 4](https://www.cloudamqp.com/blog/2015-09-03-part4-rabbitmq-for-beginners-exchanges-routing-keys-bindings.html)

### [ActiveMQ ](http://activemq.apache.org/)

Apache ActiveMQ™ is the most popular open source, multi-protocol, Java-based messaging serve

### Kafka&#x20;

Apache Kafka is a distributed event store and stream-processing platform.

* [Kafka 101 youtube](https://www.youtube.com/watch?v=j4bqyAMMb7o\&list=PLa7VYi0yPIH0KbnJQcMv5N9iW8HkZHztH), [event sourcing & event storage](https://www.youtube.com/watch?v=p\_sSRwpBkgs\&list=PLa7VYi0yPIH1TXGUoSUqXgPMD2SQXEXxj\&index=1) with Kafka - confluent
* [Web](https://kafka.apache.org/)
* [Medium - really good short intro](https://medium.com/hacking-talent/kafka-all-you-need-to-know-8c7251b49ad0)
* [Intro](https://medium.com/@jcbaey/what-is-apache-kafka-e9e73884e367), [Intro 2](https://medium.com/@patelharshali136/apache-kafka-tutorial-kafka-for-beginners-a58140cef84f),&#x20;
* [Kafka in a nutshell](https://medium.com/@aiven\_io/apache-kafka-in-a-nutshell-df10dfcc7dc) - But even these solutions came up short in some cases. For example, RabbitMQ stores messages in DRAM until the DRAM is completely consumed, at which point messages are written to disk, [severely impacting performance](https://blog.mavenhive.in/which-one-to-use-and-when-rabbitmq-vs-apache-kafka-7d5423301b58).

Also, the routing logic of AMQP can be fairly complicated as opposed to Apache Kafka. For instance, each consumer simply decides which messages to read in Kafka.

In addition to message routing simplicity, there are places where developers and DevOps staff prefer Apache Kafka for its high throughput, scalability, performance, and durability; although, developers still swear by all three systems for various reasons.

* [Apache Kafka Kafka](https://medium.com/develbyte/introduction-to-zookeeper-bcda7ef136cd) is a pub-sub messaging system. It uses Zookeeper to detect crashes, to implement topic discovery, and to maintain production and consumption state for topics.
* [Tutorial on putting a model in Kafka and using zoo keeper](https://towardsdatascience.com/putting-ml-in-production-i-using-apache-kafka-in-python-ce06b3a395c8) with code.

### KSQLDB

* KSQLDB 101 uses Kafka streams to run queries over kafka, [youtube](https://www.youtube.com/watch?v=oThQzCXjuk4\&list=PLa7VYi0yPIH3ulxsOf5g43\_QiB-HOg5\_Y)

### Zoo keeper

* Intro [1](https://medium.com/@rinu.gour123/role-of-apache-zookeeper-in-kafka-monitoring-configuration-c5bd1a7e4226), [2 - use cases](https://medium.com/@bikas.katwal10/zookeeper-introduction-designing-a-distributed-system-using-zookeeper-and-java-7f1b108e236e), [3\*](https://medium.com/@ben2460/about-apache-zookeeper-distributed-lock-1a990315e05c), [4](https://www.tutorialspoint.com/zookeeper/zookeeper\_overview.htm)
* What is [1](https://medium.com/@gavindya/what-is-zookeeper-db8dfc30fc9b), [2](https://medium.com/rahasak/apache-zookeeper-31b2091657a8)
* It is a [service discovery in a nutshell, Kafka is using it to allow discovery, registration etc of services. So that customers can subscribe and get their publication. ](https://www.quora.com/What-is-ZooKeeper)
