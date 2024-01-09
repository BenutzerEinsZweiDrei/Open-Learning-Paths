---
title: Redis
---

# [Redis](https://redis.io/)

[Hosting Redis on Fly](https://github.com/fly-apps/redis) is nice. [node-resque](https://github.com/actionhero/node-resque) is great for background jobs. [Redcon](https://github.com/tidwall/redcon) is nice Redis based server.

I use [Upstash](https://upstash.com/) as a [serverless Redis](https://www.youtube.com/watch?v=AkIGEvjsWTg).

[Mini Redis](https://github.com/tokio-rs/mini-redis) is nice code to read to understand Redis internals.

## Code

```js
// rename keys
const keys = await redis.keys("*");
for (const key of keys) {
  if (key.includes("cache:")) {
    await redis.rename(key, key.replace("cache:", ""));
  }
}
```

## Notes

- [Redis is great for shared memory across service instances. Solves the 'how can I make every instance of this app aware of something' problem. Examples: Session store backed by redis. Cache layer backed by redis. Async atomic Job queue.](https://twitter.com/bcomnes/status/1515000087163781120)

## Links

- [Scaling a High-traffic Rate Limiting Stack With Redis Cluster](https://brandur.org/redis-cluster)
- [docker-redis-cluster](https://github.com/Grokzen/docker-redis-cluster) - Dockerfile for Redis Cluster (redis 3.0+).
- [An update about Redis developments in 2019](http://antirez.com/news/126) ([HN](https://news.ycombinator.com/item?id=19227070))
- [redis-rs](https://github.com/mitsuhiko/redis-rs) - High level redis library for Rust.
- [A Multithreaded Fork of Redis That’s 5X Faster Than Redis (2019)](https://docs.keydb.dev/blog/2019/10/07/blog-post/) ([HN](https://news.ycombinator.com/item?id=21182627))
- [Redis 101: Foundation and Core Concepts (2019)](https://dev.to/mohammadhasham/redis-101-foundation-and-core-concepts-1cg6)
- [KeyDB](https://github.com/Snapchat/KeyDB) - Multithreaded Fork of Redis. ([Web](https://docs.keydb.dev/)) ([HN](https://news.ycombinator.com/item?id=36018149))
- [twemproxy](https://github.com/twitter/twemproxy) - Fast, light-weight proxy for memcached and redis.
- [RediSQL](https://github.com/RedBeardLab/rediSQL) - Fast, in-memory, SQL engine with batteries included.
- [Medis](https://github.com/luin/medis) - Beautiful, easy-to-use Mac database management application for Redis. ([Web](https://getmedis.com/))
- [How to write a Redis Client in Python, from Scratch (2020)](https://www.youtube.com/watch?v=C5KkQUKhc_4)
- [Redis Cluster Proxy](https://github.com/artix75/redis-cluster-proxy) - Proxy for Redis Clusters.
- [ioredis](https://github.com/luin/ioredis) - Robust, performance-focused and full-featured Redis client for Node.js.
- [rsedis](https://github.com/seppo0010/rsedis) - Redis re-implemented in Rust.
- [Prometheus Exporter for Redis Metrics](https://github.com/oliver006/redis_exporter)
- [mini-redis](https://github.com/tokio-rs/mini-redis) - Incomplete, idiomatic implementation of a Redis client and server built with Tokio.
- [Comparing the new Redis6 multithreaded I/O to Elasticache & KeyDB (2020)](https://docs.keydb.dev/blog/2020/04/15/blog-post/) ([HN](https://news.ycombinator.com/item?id=22879347))
- [Serverless Redis (2020)](https://medium.com/lambda-store/serverless-redis-is-here-34c2fa335f24) ([HN](https://news.ycombinator.com/item?id=22957091))
- [Redis 6.0.0 GA is out (2020)](http://antirez.com/news/132) ([HN](https://news.ycombinator.com/item?id=23030685)) ([Tweet](https://twitter.com/antirez/status/1255856794712367105))
- [Redis University](https://university.redislabs.com/) - Free online courses taught by Redis experts.
- [Hiredis](https://github.com/redis/hiredis) - Minimalistic C client library for the Redis database.
- [Improve Cache Speed at Scale (2020)](https://www.youtube.com/watch?v=mPg20ykAFU4)
- [ZanRedisDB](https://github.com/youzan/ZanRedisDB) - Distributed redis cluster with strong consistency.
- [Redis-Raft (2020)](https://jepsen.io/analyses/redis-raft-1b3fbf6) ([HN](https://news.ycombinator.com/item?id=23615790))
- [The end of the Redis adventure (2020)](http://antirez.com/news/133) ([HN](https://news.ycombinator.com/item?id=23689549))
- [Redis code](https://github.com/redis-io/redis)
- [RediSearch](https://github.com/RediSearch/RediSearch/) - Fulltext Search and Secondary Index module for Redis. ([Docs](https://oss.redislabs.com/redisearch/)) ([HN](https://news.ycombinator.com/item?id=23777460))
- [Little Redis Book](https://github.com/karlseguin/the-little-redis-book/blob/master/en/redis.md)
- [Introducing RediSearch 2.0 (2020)](https://redislabs.com/blog/introducing-redisearch-2-0/)
- [RediSQL](https://redisql.com/) - Fastest, simplest, in-memory SQL database server.
- [Redis Cluster: Architecture, Replication, Sharding and Failover (2019)](https://medium.com/opstree-technology/redis-cluster-architecture-replication-sharding-and-failover-86871e783ac0)
- [ioredis-mock](https://github.com/stipsan/ioredis-mock) - Emulates ioredis by performing all operations in-memory.
- [redismodule-rs](https://github.com/RedisLabsModules/redismodule-rs) - Idiomatic Rust API for the Redis Modules API. It allows writing Redis modules in Rust, without needing to use raw pointers or unsafe code.
- [handy-redis](https://github.com/mmkal/handy-redis) - Wrapper around node_redis with Promise and TypeScript support.
- [Pydis](https://github.com/boramalper/pydis) - Redis clone in 250 lines of Python, for performance comparison. ([HN](https://news.ycombinator.com/item?id=25100218))
- [Building a Scalable ML Feature Store with Redis (2020)](https://doordash.engineering/2020/11/19/building-a-gigascale-ml-feature-store-with-redis/)
- [Redis Website Code](https://github.com/redis/redis-io)
- [RedisJSON](https://github.com/RedisJSON/RedisJSON) - JSON data type for Redis. ([Docs](https://oss.redislabs.com/redisjson/))
- [Redis Docs](https://redis.io/documentation) ([Code](https://github.com/redis/redis-doc))
- [Titan](https://github.com/distributedio/titan) - Distributed implementation of Redis compatible layer based on TiKV.
- [fakeredis](https://github.com/jamesls/fakeredis) - Fake implementation of redis API (redis-py) for testing purposes.
- [Tendis](https://github.com/Tencent/Tendis) - High-performance distributed storage system which is fully compatible with the Redis protocol.
- [First version of Redis written in Tcl](https://gist.github.com/antirez/6ca04dd191bdb82aad9fb241013e88a8) ([HN](https://news.ycombinator.com/item?id=35989909))
- [Redis Streams and the Unified Log (2017)](https://brandur.org/redis-streams)
- [Spark-Redis](https://github.com/RedisLabs/spark-redis) - Library for reading and writing data in Redis using Apache Spark.
- [Bee-Queue](https://github.com/bee-queue/bee-queue) - Simple, fast, robust job/task queue for Node.js, backed by Redis.
- [Redis rate limiter (2021)](https://blog.rebased.pl/2021/02/22/redis-rate-limiter.html)
- [Querying, Indexing, and Full-Text Search Course](https://university.redislabs.com/courses/ru203/) - Covers RediSearch, the in-memory query, index, and search engine for Redis.
- [Awesome Redis](https://github.com/JamzyWang/awesome-redis)
- [Using Redis as an LRU cache](https://redis.io/topics/lru-cache)
- [Using Serverless Redis with Next.js (2021)](https://www.youtube.com/watch?v=FytxaSVQROc)
- [We scaled the GitHub API with a sharded, replicated rate limiter in Redis (2021)](https://github.blog/2021-04-05-how-we-scaled-github-api-sharded-replicated-rate-limiter-redis/) ([HN](https://news.ycombinator.com/item?id=26738417))
- [redis-x-stream](https://github.com/calebboyd/redis-x-stream) - AsyncIterable interface for reading redis streams.
- [Redis clone in TypeScript (2020)](https://kubej.com/redis-clone-in-typescript/)
- [Redis Input/Output Tools (RIOT)](https://github.com/redis-developer/riot) - Series of utilities designed to help you get data in and out of Redis.
- [How much faster is Redis at storing a blob of JSON compared to PostgreSQL? (2019)](https://www.peterbe.com/plog/redis-vs-postgres-blob-of-json) ([HN](https://news.ycombinator.com/item?id=26850639))
- [RedisGraph](https://github.com/RedisGraph/RedisGraph) - Graph database module for Redis. ([Docs](https://oss.redislabs.com/redisgraph/))
- [KeyDB CEO Interview: Getting into YC with a Fork of Redis](https://console.dev/qa/keydb-john-sully/) ([HN](https://news.ycombinator.com/item?id=26956846))
- [Using a disk-based Redis clone to reduce AWS S3 bill (2021)](https://wakatime.com/blog/45-using-a-diskbased-redis-clone-to-reduce-aws-s3-bill) ([HN](https://news.ycombinator.com/item?id=26955404))
- [Redis Simple Message Queue](https://github.com/smrchy/rsmq)
- [reqlite](https://github.com/augmentable-dev/reqlite) - Query Redis with SQL. ([Fork](https://github.com/redis-developer/reqlite))
- [RedisLess](https://github.com/Qovery/RedisLess) - Fast, lightweight, embedded and scalable in-memory Key/Value store library compatible with the Redis API. ([Article](https://www.heapstack.sh/redisless-blazingly-fast-serverless-redis))
- [Redis Internals](https://github.com/zpoint/Redis-Internals) - Analyze Redis 5.0 source code through diagrams.
- [Codis](https://github.com/CodisLabs/codis) - Proxy based high performance Redis cluster solution written in Go.
- [Godis](https://github.com/HDT3213/godis) - Go implementation of Redis Server.
- [Ocypod](https://github.com/davechallis/ocypod) - Language-agnostic, Redis-backed job queue server with an HTTP interface and a focus on long running tasks.
- [Redis Desktop Manager](https://github.com/qishibo/AnotherRedisDesktopManager) - Faster, better and more stable redis desktop manager.
- [Write your own Redis in Ruby](https://rohitpaulk.com/articles/redis-0)
- [Redis Geo Cache](https://github.com/fly-apps/redis-geo-cache) - Example Redis configuration that runs a primary Redis in one region and replicas in other regions.
- [Last Mile Redis (2021)](https://fly.io/blog/last-mile-redis/) ([HN](https://news.ycombinator.com/item?id=27861510))
- [Can Redis be used as a primary database? (2021)](https://www.youtube.com/watch?v=VLTPqImLapM) ([HN](https://news.ycombinator.com/item?id=28007594))
- [Redlock](https://github.com/mike-marcacci/node-redlock) - Node.js redlock implementation for distributed, highly-available redis locks.
- [Redis Inventory](https://github.com/obukhov/redis-inventory) - Tool to analyse Redis memory usage by key patterns and displaying it hierarchically.
- [redis-py](https://github.com/andymccurdy/redis-py) - Redis Python Client.
- [Fred](https://github.com/aembke/fred.rs) - Async Redis client for Rust.
- [y-redis](https://github.com/yjs/y-redis) - Redis persistence layer for Yjs.
- [Undermoon](https://github.com/doyoubi/undermoon) - Mordern Redis Cluster solution for easy operation. ([HN](https://news.ycombinator.com/item?id=28885586))
- [Undermoon Operator](https://github.com/doyoubi/undermoon-operator) - Kubernetes Operator for Redis cluster based on Undermoon.
- [Corvus](https://github.com/eleme/corvus) - Fast and lightweight Redis Cluster Proxy for Redis 3.0.
- [Redis Anti-Patterns Every Developer Should Avoid](https://developer.redis.com/howtos/antipatterns/) ([HN](https://news.ycombinator.com/item?id=28914764))
- [Build an Elixir Redis Server that’s faster than HTTP (2021)](https://docs.statetrace.com/blog/redis-server/) ([HN](https://news.ycombinator.com/item?id=29199717))
- [Redis Dataloader](https://github.com/PatrickJS/redis-dataloader) - Batching and Caching layer using Redis as the Caching layer.
- [Pika](https://github.com/OpenAtomFoundation/pika) - Persistent huge storage service , compatible with the vast majority of Redis interfaces.
- [Redigo](https://github.com/gomodule/redigo) - Go client for Redis. ([Examples](https://github.com/pete911/examples-redigo))
- [IRedis](https://iredis.io/) - Terminal Client for Redis with AutoCompletion and Syntax Highlighting. ([Code](https://github.com/laixintao/iredis))
- [Keva](https://keva.dev/) - High performance key-value store, used as Redis replacement. ([Code](https://github.com/keva-dev/keva))
- [RedisPipe](https://github.com/joomcode/redispipe) - High-throughput Redis client for Go with implicit pipelining.
- [TairHash](https://github.com/alibaba/TairHash) - Redis module, similar to redis hash, but you can set expiration and version for field.
- [Kredis](https://github.com/rails/kredis) - Higher-level data structures built on Redis.
- [Redis client Mock](https://github.com/go-redis/redismock)
- [How to build a HackerNews Clone using Redis](https://developer.redis.com/howtos/hackernews/)
- [Redis Developer Hub](https://developer.redis.com/)
- [Redis Analysis - Part 1: Threading model (2021)](https://romange.com/2021/12/09/redis-analysis-part-1-threading-model/)
- [A prelude to analysis of Redis memory-store (2021)](https://romange.com/2021/11/28/a-prelude-to-analysis-of-redis-memory-store/)
- [Rebuilding Redis in Ruby](https://redis.pjam.me/)
- [RedFI](https://github.com/openfip/redfi) - Redis Fault-Injection Proxy. Test the resiliency of your application against Redis' failures.
- [redis-semaphore](https://github.com/swarthy/redis-semaphore) - Mutex and Semaphore implementations based on Redis ready for distributed systems.
- [Bitnami Redis Docker Image](https://github.com/bitnami/bitnami-docker-redis)
- [kitteh-redis](https://github.com/djspiewak/kitteh-redis) - Toy Redis server implemented using pure FP on top of Cats Effect, Fs2, and Scodec.
- [Redis OM Node.js](https://github.com/redis/redis-om-node) - Makes it easy to model Redis data in your Node.js applications.
- [lua-resty-redis](https://github.com/openresty/lua-resty-redis) - Lua redis client driver for the ngx_lua based on the cosocket API.
- [Redis scripts do not expire keys atomically (2022)](https://ably.com/blog/redis-keys-do-not-expire-atomically) ([HN](https://news.ycombinator.com/item?id=30099572))
- [Rump](https://github.com/stickermule/rump) - Hot sync two Redis servers using dumps.
- [RedisTimeSeries](https://github.com/RedisTimeSeries/RedisTimeSeries) - Redis Module adding a Time Series data structure to Redis.
- [RedisBloom](https://github.com/RedisBloom/RedisBloom) - Probabilistic Data Structures for Redis.
- [RedisSMQ](https://github.com/weyoss/redis-smq) - Simple high-performance Redis message queue for Node.js.
- [Redis Viewer](https://github.com/SaltFishPr/redis-viewer) - Tool to view Redis data in terminal.
- [Medis](https://getmedis.com/) - GUI Manager for Redis.
- [redplex](https://github.com/microsoft/redplex) - Redis pubsub multiplexer.
- [RedisAI](https://github.com/RedisAI/RedisAI) - Redis module for serving tensors and executing deep learning graphs.
- [Redis-ImageScout](https://github.com/starkdg/Redis-ImageScout) - Redis Module for indexing of image fingerprints for fast efficient retrieval.
- [RedisGears](https://github.com/RedisGears/RedisGears) - Dynamic execution framework for your Redis data. ([Docs](https://oss.redis.com/redisgears/))
- [Upstash Redis](https://github.com/upstash/upstash-redis) - HTTP based Redis Client for Serverless and Edge Functions.
- [Redis data exposer](https://github.com/Erisa/redis-exposer) - Serve read-only Redis data over a HTTP API with auth.
- [node-resque](https://github.com/actionhero/node-resque) - Node.js Background jobs backed by redis.
- [Render Redis](https://render.com/blog/redis) ([HN](https://news.ycombinator.com/item?id=30779909))
- [Launch a Redis server on Fly](https://github.com/fly-apps/redis)
- [Redis GUI](https://github.com/ekvedaras/redis-gui) - Graphical UI for managing Redis databases.
- [Redis Stack](https://redis.io/docs/stack/) ([HN](https://news.ycombinator.com/item?id=30863327))
- [RESP.app](https://resp.app/) - Cross-platform Developer GUI for Redis. ([Code](https://github.com/uglide/RedisDesktopManager))
- [rdb](https://github.com/HDT3213/rdb) - Go implemented Redis RDB parser for secondary development and memory analysis.
- [Redis Puts (Almost) Everything Under a Single Module (2022)](https://thenewstack.io/redis-puts-almost-everything-under-a-single-module/)
- [Redis S2Geo](https://github.com/sulewicz/redis-s2geo) - Simple Redis Module for geospatial queries, which utilizes S2 Region Coverer algorithm for indexing.
- [Reimplementation of Redis in Rust](https://github.com/unrealhoang/memds)
- [Redis-Tagging](https://github.com/smrchy/redis-tagging) - NodeJS library based helper to tag (sorted) items with Redis.
- [Resque](https://github.com/resque/resque) - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
- [Webdis](https://github.com/nicolasff/webdis) - Redis HTTP interface with JSON output. ([Web](https://webd.is/))
- [RedisInsight](https://redis.com/redis-enterprise/redis-insight/) - Official Redis GUI.
- [Redis RDB Tools](https://github.com/sripathikrishnan/redis-rdb-tools) - Parse Redis dump.rdb files, Analyze Memory, and Export Data to JSON.
- [Lua Resty qless](https://github.com/ledgetech/lua-resty-qless) - Lua binding to Qless (Queue / Pipeline management) for OpenResty / Redis.
- [SRH](https://github.com/hiett/serverless-redis-http) - HTTP-based Redis pooler. Access Redis from serverless without overloading connection limits.
- [RedisInsight](https://github.com/RedisInsight/RedisInsight) - Developer GUI for Redis, by Redis.
- [RedisEdge Real-time Video Analytics](https://github.com/RedisGears/EdgeRealtimeVideoAnalytics) - Example of using Redis Streams, RedisGears, RedisAI, and RedisTimeSeries for Real-time Video Analytics.
- [Redis Operator](https://github.com/spotahome/redis-operator) - Creates/configures/manages redis-failovers atop Kubernetes.
- [Tidis](https://github.com/yongman/tidis) - Distributed transactional NoSQL database, Redis protocol compatible using tikv as backend.
- [gotway](https://github.com/gotway/gotway) - Cloud native API Gateway powered with in-redis cache.
- [Redcon.rs](https://github.com/tidwall/redcon.rs) - Redis compatible server framework for Rust.
- [RoseDB](https://github.com/flower-corp/rosedb) - High performance NoSQL database based on bitcask, supports string, list, hash, set, and sorted set. Similar to Redis but store values on disk.
- [RediSearch](https://redis.io/docs/stack/search/) - Queries, secondary indexing, and full-text search for Redis. ([Go Client](https://github.com/RediSearch/redisearch-go))
- [Redust](https://github.com/appellation/redust) - Simple Redis client & RESP parser for Rust.
- [Redis Analysis - Part 1: Threading model (2021)](https://www.romange.com/2021/12/09/redis-analysis-part-1-threading-model/)
- [Redis PubSub](https://github.com/soundxyz/redis-pubsub) - Full type-safe Redis PubSub with Zod.
- [RedisRaft](https://github.com/RedisLabs/redisraft) - Redis Module that make it possible to create a consistent Raft cluster from multiple Redis instances.
- [Docker and Redis - a curious beginner’s walkthrough (2022)](http://blog.miranti.net.br/redis-getting-started)
- [Redis vs. KeyDB vs. Dragonfly vs. Skytable (2022)](https://news.ycombinator.com/item?id=31796311)
- [Go Rate Limiter interface for Redis](https://github.com/sethvargo/go-redisstore)
- [walrus](https://github.com/coleifer/walrus) - Lightweight Python utilities for working with Redis.
- [Redis-Shake](https://github.com/alibaba/RedisShake) - Tool for synchronizing data between two redis databases.
- [redfront](https://github.com/tidwall/redfront) - HTTP protocol frontend for Redis-compatible services.
- [Rip](https://github.com/zdenham/redis-ipfs) - Redis Key Value store backed by IPFS.
- [Redis-Rope](https://github.com/ekzhang/redis-rope) - Fast native data type for manipulating large strings in Redis.
- [Redis Replica Manager](https://github.com/zavitax/redis-replica-manager-go) - Group membership, sharding, replication and request routing manager relying on Redis for coordination.
- [How to Reduce Latency and Minimize Outages (2022)](https://redis.com/blog/how-to-reduce-latency-and-minimize-outages/)
- [Redis explained (2022)](https://architecturenotes.co/redis/) ([HN](https://news.ycombinator.com/item?id=32426879))
- [bitmapist](https://github.com/Doist/bitmapist) - Powerful analytics and cohort library using Redis bitmaps.
- [Redis Cache](https://github.com/go-redis/cache) - Cache library with Redis backend for Go.
- [Visual and Semantic Similarity with Redis](https://github.com/RedisAI/vecsim-demo)
- [How Gas app cut its Redis Engine CPU Utilization by 80% (2022)](https://twitter.com/daveschatz/status/1583342175005220864) ([Lobsters](https://lobste.rs/s/gzkgho/how_gas_app_cut_its_redis_engine_cpu))
- [Redis Oxide](https://github.com/dpbriggs/redis-oxide) - Multi-threaded implementation of redis written in rust.
- [Dice](https://github.com/DiceDB/dice) - Extremely simple Go-based in-memory KV store that speaks the Redis dialect.
- [Launching Redis by Upstash (2022)](https://fly.io/blog/launching-redis-by-upstash/) ([HN](https://news.ycombinator.com/item?id=34005991))
- [r2d2](https://github.com/iuioiua/r2d2) - Fast, lightweight Redis client library for Deno.
- [rueidis](https://github.com/rueian/rueidis) - Fast Go Redis client that supports Client Side Caching, Auto Pipelining, Generics OM, RedisJSON, RedisBloom, RediSearch, etc.
- [Redis Data Types: The Basics (2022)](https://thenewstack.io/redis-data-types-the-basics/)
- [Intro to Redis Scripting with Lua (2023)](https://www.novus.com/tech-blog/intro-to-redis-scripting-with-lua)
- [Aedis](https://github.com/mzimbres/aedis) - Async redis client designed for performance and scalability in C++.
- [fakeredis](https://github.com/cunla/fakeredis-py) - Fake version of a redis-py.
- [Build Your Own Redis with C/C++](https://build-your-own.org/redis/) ([HN](https://news.ycombinator.com/item?id=34572263)) ([HN](https://news.ycombinator.com/item?id=35212660))
- [Optimizing Redis’ Default Compiler Flags (2023)](https://redis.com/blog/optimizing-redis-compiler-flags/)
- [rustis](https://github.com/dahomey-technologies/rustis) - Asynchronous Redis client for Rust.
- [Consistent caching with PostgreSQL logical replication and a Redis API (2023)](https://shortishly.com/blog/streaming-replication-redis-api/)
- [redis-cell](https://github.com/brandur/redis-cell) - Redis module that provides rate limiting in Redis as a single command.
- [coredis](https://github.com/alisaifee/coredis) - Async redis client for python with support for redis cluster & sentinel.
- [reddish](https://github.com/stereobutter/reddish) - Async redis client for python with minimal API.
- [Go Typed Redis Streams](https://github.com/dranikpg/gtrs)
- [Redis Interval Sets](https://github.com/danitseitlin/redis-interval-sets) - Redis module for creating interval sets, handling them and filtering out relevant sets by number in range.
- [Redis Data Source for Grafana](https://github.com/RedisGrafana/grafana-redis-datasource)
- [RedisRaft](https://github.com/RedisLabs/redisraft/blob/master/docs/Introduction.md) ([HN](https://news.ycombinator.com/item?id=35847269))
- [Story: Redis and its creator antirez (2023)](https://blog.brachiosoft.com/redis-en) ([HN](https://news.ycombinator.com/item?id=35871462))
- [Redis Dump](https://github.com/upstash/upstash-redis-dump) - Dumps Redis keys & values to a file.
- [Rudis](https://github.com/lorenzoc25/rudis) - Sharded, concurrent mini redis that support http interface implemented in rust.
- [RedHub](https://github.com/IceFireDB/redhub) - High-performance Redis-Server multi-threaded framework, based on rawepoll model.
