# Message Brokers Solutions & Cloud Technologies

## Open Source Message Brokers

- [Apache Kafka](https://kafka.apache.org/): The most popular open-source message broker nowadays. Apache Kafka is a distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.
- [RabbitMQ](https://www.rabbitmq.com/): A widely deployed open-source message broker. It is used worldwide at small startups and large enterprises.

## Cloud Based Message Brokers

- [Amazon Simple Queue Service (SQS)](https://aws.amazon.com/sqs/): Fully managed message queuing service that enables you to decouple and scale micro-services, distributed systems, and serverless applications.
- **Google Cloud Platform** [Pub/Sub](https://cloud.google.com/pubsub/docs/overview) and [Cloud Tasks](https://cloud.google.com/tasks/docs/dual-overview): Publisher/Subscriber and message queue solutions offered by Google Cloud Platform. See [this article](https://cloud.google.com/pubsub/docs/choosing-pubsub-or-cloud-tasks) for comparison between the two offerings.
- **Microsoft Azure**:
  - [Service Bus](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview): Fully managed enterprise message broker with message queues and publish-subscribe topics.
  - [Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs/): Fully managed real-time data ingestion service. Allows streaming millions of events per second from any source. Integrates seamlessly with Apache Kafka clients without any code changes. A perfect solution for Big Data.
  - [Event Grid](https://azure.microsoft.com/en-us/products/event-grid/): Reliable, serverless event delivery system at a massive scale. It uses the publish-subscribe model. It is Dynamically scalable, Low cost with a pay-as-you-go model, and guarantees "At least once delivery of an event".
