## Amazon Simple Queue Service (SQS) - Managed message queues

- Amazon SQS is `a fully managed message queuing service` that enables you to `decouple and scale microservices, distributed systems, and serverless applications`

- Using Amazon SQS, you can `send, store, and receive messages between software components` at any volume, without losing messages or requiring other services to be available

- SQS offers two types of message queues

  - Standard queues: Offer `maximum throughput, best-effort ordering, and at-least-once delivery`
  - SQS FIFO: Guarantee that `messages are processed exactly once, in the exact order`

- Default retention of messages is 4 days, maximum 14 days

- `No limit messages on the queue` and the messages `will be deleted after they're read by consumers`
