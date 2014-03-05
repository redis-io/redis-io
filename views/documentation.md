Documentation
===

Note: the Redis documentation is also available in raw (computer friendly) format in the [redis-doc github repository](http://github.com/antirez/redis-doc).

Programming with Redis
---

* [The full list of commands](/commands) implemented by Redis, along with thorough documentation for each of them.
* [Pipelining](/topics/pipelining): Learn how to send multiple commands
at once, saving on round trip time.
* [Redis Pub/Sub](topics/pubsub): Redis is a fast and stable Publish/Subscribe messaging system! Check it out.
* [Redis Lua scripting](/commands/eval): Redis 2.6 Lua scripting feature documentation.
* [Memory optimization](/topics/memory-optimization): Understand how
Redis uses RAM and learn some tricks to use less of it.
* [Expires](/commands/expire): Redis allows to set a time to live different for every key so that the key will be automatically removed from the server when it expires.
* [Redis transactions](/topics/transactions): It is possible to group commands together so that they are executed as a single transaction.
* [Mass insertion of data](/topics/mass-insert): How to add a big amount of pre existing or generated data to a Redis instance in a short time.
* [Partitioning](/topics/partitioning): How to distribute your data among multiple Redis instances.
* [Redis keyspace notifications](/topics/notifications): Get notifications of keyspace events via Pub/Sub. This feature was recently merged into the unstable branches. The first stable release of this implementation will be in Redis 2.8.

Administration
---
* [Configuration](/topics/config): How to configure redis.
* [Replication](/topics/replication): What you need to know in order to
set up master-slave replication.
* [Persistence](/topics/persistence): Know your options when configuring
Redis' durability.
* [Redis Administration](/topics/admin): Selected administration topics.
* [Security](/topics/security): An overview of Redis security.
* [Signals Handling](/topics/signals): How Redis handles signals.
* [Connections Handling](/topics/clients): How Redis handles clients connections.
* [High Availability](/topics/sentinel): Redis Sentinel is the official high availability solution for Redis. Currently work in progress (beta stage, active development), already usable.
* [Benchmarks](/topics/benchmarks): See how fast Redis is in different platforms.
* [Redis Releases](/topics/releases): Redis development cycle and version numbering.

Troubleshooting
---

* [Redis problems?](/topics/problems): Bugs? High latency? Other issues? Use [our problems troubleshooting page](/topics/problems) as a starting point to find more information.

Redis Cluster
---
* [Redis Cluster tutorial](/topics/cluster-tutorial): a gentle introduction and setup guide to Redis Cluster (currently not production ready, but usable).
* [Redis Cluster specification](/topics/cluster-spec): the more formal description of the behavior and algorithms used in Redis Cluster.

Specifications
---

* [Redis Design Drafts](/topics/rdd): Design drafts of new proposals.
* [Redis Protocol specification](/topics/protocol): if you're implementing a
client, or out of curiosity, learn how to communicate with Redis at a
low level.
* [Redis RDB format](https://github.com/sripathikrishnan/redis-rdb-tools/wiki/Redis-RDB-Dump-File-Format) specification, and [RDB version history](https://github.com/sripathikrishnan/redis-rdb-tools/blob/master/docs/RDB_Version_History.textile).
* [Internals](/topics/internals): Learn details about how Redis is implemented under the hood.

Tutorials & FAQ
---

* [FAQ](/topics/faq): Some common questions about Redis.
* [Data types](/topics/data-types): A summary of the different types of values that Redis supports.
* [15 minutes introduction to Redis data types](/topics/data-types-intro)
* [Writing a simple Twitter clone with PHP and Redis](/topics/twitter-clone)
* [Auto complete with Redis](http://antirez.com/post/autocomplete-with-redis.html)

Presentations
-------------

* Salvatore Sanfilippo: [Redis cluster overview](/presentation/Redis_Cluster.pdf)
* Pieter Noordhuis: [What's new in Redis 2.2](/presentation/Pnoordhuis_whats_new_in_2_2.pdf)

If you would like to include the logo in a presentation, please use the
[high-res version](/images/redis-300dpi.png). The [svg version is also available](/images/redis-logo.svg).


Use cases
---
* [Who is using Redis](/topics/whos-using-redis)

Books
---

The following is a list of books covering Redis that are already published:

* [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/) by [Karl Seguin](http://twitter.com/karlseguin) is a great *free* and concise book that will get you started with Redis.
* [Redis in Action](http://www.manning.com/carlson/) by [Josiah L. Carlson](http://twitter.com/dr_josiah) (early access edition).
* [Redis Cookbook (O'Reilly Media, 2011)](http://shop.oreilly.com/product/0636920020127.do)

The following books have Redis related content but are not specifically about Redis:

* [Seven databases in seven weeks](http://pragprog.com/book/rwdata/seven-databases-in-seven-weeks) (Note: Redis chapter still coming soon).
* [Mining the Social Web (O'Reilly Media, 2011)](http://shop.oreilly.com/product/0636920010203.do)
* [Professional NoSQL (Wrox, 2011)](http://www.wrox.com/WileyCDA/WroxTitle/Professional-NoSQL.productCd-047094224X.html)

Credits
---

Redis is maintained and developed by [Salvatore Sanfilippo](http://twitter.com/antirez). [Pieter Noordhuis](http://twitter.com/pnoordhuis) provided a very significant amount of code and ideas to both the Redis core and a number of client libraries.

The full list of Redis contributors can be found in the [Redis contributors page at Github](https://github.com/antirez/redis/graphs/contributors). However there are other forms of contributions such as ideas, testing, and bug reporting. When possible this contributions are acknowledged in the commit messages. The [mailing list archives](http://groups.google.com/group/redis-db) and the [Github issues page](https://github.com/antirez/redis/issues) are good sources to find people active in the Redis community providing ideas and helping other users.

Sponsors
---

The work [Salvatore Sanfilippo](http://antirez.com) do in order to develop Redis is sponsored by [Pivotal](http://gopivotal.com). In the past the Redis project was sponsored and accepted donations from other companies that are listed in the [Sponsors page](/topics/sponsors).
