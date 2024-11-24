# awesome-streaming （ Streaming引擎与框架精选 ）

以下是为中国用户优化的流处理引擎、框架和相关工具列表，去除了小众、不常用和过时内容，重点关注主流、实用工具。

---

### 流处理引擎

- **[Apache Flink](https://github.com/apache/flink)** [Java]  
  高吞吐、低延迟的流处理系统，支持有状态计算、窗口计算和迭代流处理。
  
- **[Apache Spark Streaming](https://github.com/apache/spark)** [Scala]  
  构建可扩展、容错流处理应用程序的流行框架。
  
- **[Apache Storm](https://github.com/apache/storm)** [Java]  
  分布式实时计算系统，适用于流处理。

- **[Apache Kafka Streams](https://github.com/apache/kafka)** [Java]  
  轻量级流处理库，与Kafka无缝集成，适用于实时分析。

- **[Bytewax](https://github.com/bytewax/bytewax)** [Python]  
  基于Python的分布式、有状态流处理框架，适合快速开发。

- **[RisingWave](https://github.com/risingwavelabs/risingwave)** [Rust]  
  支持PostgreSQL兼容的流数据库，适用于实时ETL、连续分析和事件驱动应用。

- **[Materialize](https://materialize.com)** [Rust]  
  支持持续SQL查询的流处理数据库。

---

### 数据管道与消息中间件

- **[Apache Kafka](https://github.com/apache/kafka)** [Scala/Java]  
  分布式、分区、可复制的提交日志服务，广泛用于消息和数据流处理。

- **[Apache Pulsar](https://github.com/apache/pulsar)** [Java]  
  灵活的分布式发布/订阅消息平台，支持多租户和延迟队列。

- **[Redpanda](https://github.com/redpanda-data/redpanda)** [C++]  
  Kafka兼容的高性能分布式流平台，消除了对ZooKeeper和JVM的依赖。

- **[RocketMQ](https://github.com/apache/rocketmq)** [Java]  
  高性能、可靠的分布式消息与流处理平台，适用于大规模系统。

---

### 在线机器学习

- **[River](https://github.com/online-ml/river)** [Python]  
  在线机器学习库，支持实时数据流的增量学习。

- **[Apache Samoa](https://github.com/apache/incubator-samoa)** [Java]  
  用于流式机器学习的分布式框架。

---

### 流处理SQL

- **[ksqlDB](https://github.com/confluentinc/ksql)** [Java]  
  用于流处理的开源SQL引擎，与Kafka无缝集成。

- **[Siddhi](https://github.com/siddhi-io/siddhi)** [Java]  
  支持复杂事件处理的流SQL引擎，适用于实时分析。

---

### 边缘流处理

- **[Kuiper](https://github.com/emqx/kuiper)** [Go]  
  轻量级的边缘流处理引擎，专为资源受限设备设计。

---

### 工具与阅读推荐

#### 工具

- **[Akka Streams](https://github.com/akka/akka)** [Scala]  
  基于Actor模型的流处理库，适用于高并发和分布式系统。

- **[Benthos](https://github.com/Jeffail/benthos)** [Go]  
  高性能消息流处理服务，支持多种数据源和接收器。

#### 推荐阅读

1. [The World Beyond Batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html)  
2. [Streaming Systems](https://www.oreilly.com/library/view/streaming-systems/9781491983867/)  
3. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems)  
