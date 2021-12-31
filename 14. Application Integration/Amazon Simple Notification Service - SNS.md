## Amazon Simple Notification Service (SNS) - Pub/Sub, SMS, email, and mobile push notifications

- Amazon Simple Notification Service is `a managed service` that `provides message delivery from publishers to subscribers`(Pub/Sub)

- `Publishers communicate asynchronously with subscribers by sending messages to a topic`, which is a logical access point and communication channel

- SQS offers two types of message queues

  - Standard queues: Offer `maximum throughput, best-effort ordering, and at-least-once delivery`
  - SQS FIFO: Guarantee that `messages are processed exactly once, in the exact order`

- Clients can subscribe to the SNS topic and receive published messages using a supported endpoint type, such as

  - Amazon Kinesis Data Firehose
  - Amazon SQS
  - AWS Lambda
  - HTTP
  - Email
  - Mobile push notifications
  - Mobile text messages (SMS)
