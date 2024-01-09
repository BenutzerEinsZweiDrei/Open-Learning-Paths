---
title: Message queue
---

# [Message queue](https://en.wikipedia.org/wiki/Message_queue)

[Never ever use a database as a message queue](https://blog.chiselstrike.com/dear-application-developer-how-far-can-you-really-go-without-a-message-queue-d9e5385fab64) is great read.

## Links

- [patchbay](https://patchbay.pub/) - Message queue implemented over HTTP. ([Lobsters](https://lobste.rs/s/t8dsft/patchbay_poor_man_s_message_queue))
- [ElasticMQ](https://github.com/softwaremill/elasticmq) - Message queue system, offering an actor-based Scala and an SQS-compatible REST (query) interface.
- [Disque](https://github.com/antirez/disque-module) - Ongoing experiment to build a distributed, in-memory, message broker.
- [rmq](https://github.com/adjust/rmq) - Message queue system written in Go and backed by Redis.
- [BullMQ](https://github.com/taskforcesh/bullmq) - Premium Message Queue for NodeJS based on Redis.
- [Celery](https://github.com/celery/celery) - Distributed Task Queue. ([Docs](https://docs.celeryproject.org/en/stable/index.html))
- [Rusty Celery](https://github.com/rusty-celery/rusty-celery) - Rust implementation of Celery for producing and consuming background tasks. ([Docs](https://rusty-celery.github.io/))
- [Apache RocketMQ](https://github.com/apache/rocketmq) - Distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity and flexible scalability.
- [Performance benchmarks for various message queues](https://github.com/tylertreat/mq-benchmarking)
- [Everything You Need To Know About Message Queues (2020)](https://sunilkumarc.in/everything-you-need-to-know-about-message-queues)
- [How do I design a system to process messages sequentially (2020)](https://lobste.rs/s/w1bk6l/how_do_i_design_system_process_messages)
- [The Big Little Guide to Message Queues (2020)](https://sudhir.io/the-big-little-guide-to-message-queues/) ([HN](https://news.ycombinator.com/item?id=25591492))
- [Machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
- [MiniQueue](https://github.com/tomarrell/miniqueue) - Simple, single binary, message queue.
- [Broker](https://github.com/apibillme/broker) - Real-time BaaS (Backend as a Service). SSE message broker that requires you write no backend code to have a full real-time API.
- [JackRabbit](https://github.com/apibillme/jackrabbit) - Real-time Message Queue.
- [MQ](https://github.com/asim/mq) - Simple distributed in-memory message broker.
- [nerve](https://github.com/queer/singyeong) - Cloud-native messaging/pubsub with powerful routing.
- [Thoughts on inter-service messaging (2021)](https://b.amy.gg/thoughts-on-inter-service-messaging)
- [Plumber](https://github.com/batchcorp/plumber) - Swiss army knife CLI tool for interacting with Kafka, RabbitMQ and other messaging systems.
- [SimpleXMQ](https://github.com/simplex-chat/simplexmq) - Message broker for managing message queues and sending messages over public network.
- [Apache ActiveMQ](https://activemq.apache.org/) - Popular open source, multi-protocol, Java-based message broker. ([Code](https://github.com/apache/activemq)) ([Docker](https://github.com/disaster37/activemq))
- [Burlesque](https://github.com/KosyanMedia/burlesque) - Message queue server with HTTP interface.
- [Floki Message Queue](https://github.com/arthurprs/floki) - Borrows concepts from both Kafka and Amazon SQS into an easy to use package.
- [Great hosted message queues](https://twitter.com/jevakallio/status/1507367310352396320)
- [Cavalcade](https://github.com/palfrey/cavalcade) - AMQP broker backed by PostgreSQL.
- [A Message Queue in Shell](https://pencil.toast.cafe/wt2om7i8t7) ([Lobsters](https://lobste.rs/s/p2hlkz/message_queue_shell))
- [SAQ](https://github.com/tobymao/saq) - Simple Async Queues. Simple and performant job queueing framework built on top of asyncio and redis.
- [Bull Dashboard](https://github.com/felixmosh/bull-board) - UI built on top of Bull or BullMQ to help you visualize your queues and their jobs.
- [dispenserd](https://github.com/realtux/dispenserd) - Job queue designed to be: fast, reliable, feature rich, and tailored towards the needs of developers.
- [Message Broker](https://github.com/prodoxx/message-broker) - Simple message broker example using BullMQ and Redis (worker / queue).
- [Valet](https://github.com/svaloumas/valet) - Job queuing service and async task runner.
- [Bonsaimq](https://github.com/FlixCoder/bonsaimq) - Simple database message queue based on bonsaidb.
- [Awesome Queues](https://github.com/tonyhb/awesome-queues-jobs-and-tasks) - Curated list of awesome queueing systems for background jobs and distributed tasks.
- [Never ever use a database as a message queue (2022)](https://blog.chiselstrike.com/dear-application-developer-how-far-can-you-really-go-without-a-message-queue-d9e5385fab64) ([HN](https://news.ycombinator.com/item?id=32563909))
- [LavinMQ](https://github.com/cloudamqp/lavinmq) - A message queue server that implements the AMQP protocol. Written in Crystal.
- [Write Your Own Task Queue (2022)](https://danpalmer.me/2022-09-10-write-your-own-task-queue/)
- [Pulsar](https://github.com/apache/pulsar) - Distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
- [BullMQ with BullBoard](https://github.com/railwayapp-templates/fastify-bullmq) - Template repository to deploy a robust queueing system on Railway using BullMQ and Redis.
- [pgmq](https://github.com/adriangb/pgmq) - Message queue built on top of Postgres.
- [laminarmq](https://github.com/arindas/laminarmq) - Scalable, distributed message queue powered by a segmented, partitioned, replicated and immutable log.
- [sqlxmq](https://github.com/Diggsey/sqlxmq) - Message queue implemented on top of PostgreSQL.
- [Message Queue](https://github.com/imqueue/core) - Simple JSON-based messaging queue for inter service communication.
- [Message Queue RPC](https://github.com/imqueue/rpc) - RPC-like client-service implementation over messaging queue.
- [Conveyor MQ](https://github.com/conveyor-mq/conveyor-mq) - Fast, robust and extensible distributed task/job queue for Node.js, powered by Redis.
- [Replicating Database Changes to a Message Queue is Tricky (2022)](https://www.evanjones.ca/replicating-db-to-queue.html)
- [Ratus](https://github.com/hyperonym/ratus) - RESTful asynchronous task queue server.
- [mq](https://github.com/prabirshrestha/mq) - Generic simple message queue library for rust.
- [Anything can be a message queue if you use it wrongly enough (2023)](https://xeiaso.net/blog/anything-message-queue) ([HN](https://news.ycombinator.com/item?id=36186176))
- [Message Queues: Function and Role in ML Inference](https://github.com/arindas/tfug-ml-mq-infer)
