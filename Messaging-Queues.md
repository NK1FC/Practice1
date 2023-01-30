# Messaging Queues

## Introduction
Messaging Queues, commonly referred to as Message brokers, are a sort of software architecture that permits communication between programs. Applications can use them to send and receive messages asynchronously, which means that neither the sender nor the recipient must be active at the same moment. The ability to decouple between components and enable loosely-coupled communication across the components makes messaging queues a powerful tool for creating scalable and resilient systems. 
## Benefits of Using Messaging Queue
* Asynchronous communication: Applications can interact asynchronously with the use of messaging queues, allowing the sender and receiver to work separately from one another. This is helpful when one component cannot react to a request instantly or when it is not essential for the response to be received right away.
 * Load balancing: Messaging queues can be used to spread workloads evenly among many systems. For instance, incoming requests can be sent to several worker nodes via a message queue so that they can be handled concurrently.
 * Decoupling: Messaging queues enable loosely-coupled communication across components, ensuring that changes to one component have no impact on the others. Complex systems can now be built and maintained more easily since individual components can be changed without affecting the entire system.
 * Resilience: Messaging queues are made with high availability and scalability in mind, which makes them perfect for use in mission-critical systems. When one component is down, it can be utilized to buffer messages and, if necessary, automatically retry transmitting messages.
  ## Popular Tools for Messaging Queues
  * [RabbitMQ](https://www.rabbitmq.com/)
  * [IBM MQ](https://www.ibm.com/in-en/products/mq)
  * [Apache Kafka](https://kafka.apache.org/) 
  * [Amazon SQS](https://aws.amazon.com/sqs/)
  * [Red Hat AMQ](https://www.redhat.com/en/technologies/jboss-middleware/amq)
  ## Enterprise Message Bus
  An Enterprise Service Bus (ESB) is used to distribute work among connected application components. With the capacity to connect to the ESB and subscribe to messages based on basic structural and business policy rules, it is intended to provide a uniform method of moving work. It typically consists of a set of message queues that are connected by a set of routing rules. Applications send messages to the message bus, which then routes the messages to the appropriate queues based on the routing rules.

  ## Benefits of Using Enterprise Message Bus
* An enterprise message bus provides a centralized communication layer for large-scale, complex systems, which makes it easier to manage and maintain the communication between components.
* An enterprise message bus provides a standardized way for applications to communicate with each other, which makes it easier to build and maintain complex systems.
* An enterprise message bus is designed to be highly scalable, which makes it ideal for use in large-scale, complex. 


## References
* Vimal, Ranjeet. "Message Queues — 10 Reasons to Use Message Queuing" Medium, 23 May 2017, https://medium.com/@ranjeetvimal/message-queues-10-reasons-to-use-message-queuing-1923277a2e7f
* IBM Technology. "What is a Message Queue?" Youtube, 10 Jan. 2022, https://www.youtube.com/watch?v=xErwDaOc-Gs&t=377s
* Gaurav Sen. "What is a Message Queue and Where is it used?" Youtube, 7 May 2018, https://www.youtube.com/watch?v=oUJbuFMyBDk&t=200s
* Tolety, Kavya, "Popular Message Broker Platforms for 2023" Hevo, 9 Jan. 2023, https://hevodata.com/learn/popular-message-broker/
* Amazon. "What is a Message Queue?". Retrieved from https://aws.amazon.com/message-queue/
* Amazon. "Benefits of Message Queues". Retrieved from https://aws.amazon.com/message-queue/benefits/  
* Churchville, Fred. "Enterprise Service Bus (ESB)" TechTarget, https://www.techtarget.com/searchapparchitecture/definition/Enterprise-Service-Bus-ESB
* Coursible. "Introduction to Enterprise Service Bus" Youtube, 14 oct. 2016, https://www.youtube.com/watch?v=cW9SiCH0kYs   
* CData Arc Marketing, "Modern ESBs: Pros & Cons" Cdata, 14 Jan. 2020, https://arc.cdata.com/blog/20200114-modern-esb