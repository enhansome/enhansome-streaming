# Awesome streaming with stars

## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 499,154 | 🐛 106 | 📅 2026-08-21 [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions) ⭐ 3,007 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-22

A curated list of awesome [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) frameworks, applications, readings and other resources. Inspired by [other awesome projects](https://github.com/sindresorhus/awesome) ⭐ 499,154 | 🐛 106 | 📅 2026-08-21.

## Website

<https://manuzhang.github.io/awesome-streaming/> is a more dynamic website where you can find **updates** of the awesome projects here.

## Table of Contents

* [Engines and Platforms](#engines-and-platforms)
* [Libraries, SDKs, and Programming Models](#libraries-sdks-and-programming-models)
* [Data Integration and Pipelines](#data-integration-and-pipelines)
* [Applications and Tools](#applications-and-tools)
* [Managed and Closed Source](#managed-and-closed-source)
* [Benchmarks](#benchmarks)
* [Readings](#readings)

### Engines and Platforms

* [Apache Spark Streaming](https://github.com/apache/spark) ⭐ 43,864 | 🐛 472 | 🌐 Scala | 📅 2026-08-23 <sub>![Scala/Java/Python/R][language-scala-java-python-r]</sub> - Scalable, fault-tolerant stream processing on Apache Spark.
* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,597 | 🐛 515 | 🌐 Java | 📅 2026-08-23 <sub>![Java/Scala][language-java-scala]</sub> - Distributed event streaming platform for high-performance data pipelines and applications.
* [Apache Flink](https://github.com/apache/flink) ⭐ 26,280 | 🐛 375 | 🌐 Java | 📅 2026-08-22 <sub>![Java][language-java]</sub> - Distributed engine for stateful computation over bounded and unbounded data streams.
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,772 | 🐛 77 | 🌐 Go | 📅 2026-08-11 <sub>![Go][language-go]</sub> - Real-time distributed messaging platform designed to operate at scale.
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,562 | 🐛 563 | 🌐 Java | 📅 2026-08-20 <sub>![Java][language-java]</sub> - Cloud-native messaging and streaming platform for event-driven applications.
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,311 | 🐛 1,751 | 🌐 Java | 📅 2026-08-20 <sub>![Java][language-java]</sub> - Distributed pub-sub messaging and event streaming platform.
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,471 | 🐛 590 | 🌐 C++ | 📅 2026-08-22 <sub>![C++][language-cpp]</sub> - Kafka API-compatible streaming data platform without ZooKeeper or a JVM.
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,545 | 🐛 61 | 🌐 Java | 📅 2026-08-21 <sub>![Java/Scala][language-java-scala]</sub> - Diskless Kafka-compatible streaming platform that stores durable data in object storage.
* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,283 | 🐛 1,604 | 🌐 Rust | 📅 2026-08-23 <sub>![Rust][language-rust]</sub> - PostgreSQL-compatible streaming database for event-driven applications, real-time ETL, and continuous analytics.
* [Aeron](https://github.com/aeron-io/aeron) ⭐ 8,812 | 🐛 23 | 🌐 Java | 📅 2026-08-23 <sub>![Java/C++][language-java-cpp]</sub> - Reliable UDP unicast, multicast, and IPC message transport.
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,698 | 🐛 44 | 🌐 Java | 📅 2026-08-22 <sub>![Java][language-java]</sub> - Distributed real-time computation system for reliably processing unbounded streams of data.
* [Fluvio](https://github.com/fluvio-community/fluvio) ⭐ 5,246 | 🐛 141 | 🌐 Rust | 📅 2026-08-20 <sub>![Rust/WASM][language-rust-wasm]</sub> - Composable, stateful data streaming system with programmable in-line computation.
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,012 | 🐛 120 | 🌐 Rust | 📅 2026-08-20 <sub>![Rust][language-rust]</sub> - Distributed stream processing engine for stateful SQL computations over unbounded data.
* [Apache Heron](https://github.com/apache/incubator-heron) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed, fault-tolerant stream processing engine originally developed at Twitter.
* [Numaflow](https://github.com/numaproj/numaflow) ⭐ 2,825 | 🐛 286 | 🌐 Rust | 📅 2026-08-22 <sub>![Rust/Go/TypeScript][language-rust-go-typescript]</sub> - Kubernetes-native, language-agnostic platform for scalable event-driven applications.
* [PipelineDB](https://github.com/pipelinedb/pipelinedb) ⭐ 2,662 | 🐛 133 | 🌐 C | 📅 2022-02-20 <sub>![Archived][archived-badge]</sub> <sub>![C][language-c]</sub> - Unmaintained PostgreSQL extension for continuous SQL aggregation over time-series data.
* [NATS Streaming](https://github.com/nats-io/nats-streaming-server) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Deprecated disk-backed messaging system superseded by NATS JetStream.
* [Proton](https://github.com/timeplus-io/proton) ⭐ 2,245 | 🐛 80 | 🌐 C++ | 📅 2026-08-13 <sub>![C++][language-cpp]</sub> - Unified streaming and historical data analytics database powered by ClickHouse.
* [Onyx](https://github.com/onyx-platform/onyx) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Clojure][language-clojure]</sub> - Distributed, masterless, fault-tolerant data processing platform.
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,047 | 🐛 37 | 🌐 Python | 📅 2026-06-20 <sub>![Python/Rust][language-python-rust]</sub> - Community-maintained Python framework with a Rust-based distributed engine for stateful stream processing.
* [LogDevice](https://github.com/facebookarchive/LogDevice) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Facebook's archived distributed storage system for sequential data.
* [eKuiper](https://github.com/lf-edge/ekuiper) ⭐ 1,730 | 🐛 49 | 🌐 Go | 📅 2026-08-19 <sub>![Go][language-go]</sub> - Lightweight data stream processing engine for resource-constrained IoT edge devices.
* [Siddhi](https://github.com/siddhi-io/siddhi) ⭐ 1,589 | 🐛 125 | 🌐 Java | 📅 2026-05-05 <sub>![Java][language-java]</sub> - Streaming SQL and complex event processing engine.
* [Wally](https://github.com/WallarooLabs/wally) ⭐ 1,482 | 🐛 348 | 🌐 Pony | 📅 2021-04-06 <sub>![Archived][archived-badge]</sub> <sub>![Pony][language-pony]</sub> - Distributed stream processing framework formerly named Wallaroo.
* [Mantis](https://github.com/Netflix/mantis) ⭐ 1,470 | 🐛 92 | 🌐 Java | 📅 2026-08-21 <sub>![Java][language-java]</sub> - Netflix platform for building real-time, operations-focused stream processing applications.
* [Metaq](https://github.com/killme2008/Metamorphosis) ⭐ 1,329 | 🐛 49 | 🌐 Java | 📅 2020-04-07 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Taobao distributed messaging system.
* [ArkFlow](https://github.com/arkflow-rs/arkflow) ⭐ 1,301 | 🐛 31 | 🌐 Rust | 📅 2026-08-16 <sub>![Rust][language-rust]</sub> - High-performance stream processing engine with pluggable sources, processors, and sinks.
* [Trill](https://github.com/microsoft/Trill) ⭐ 1,271 | 🐛 49 | 🌐 C# | 📅 2024-01-08 <sub>![Archived][archived-badge]</sub> <sub>![C#][language-csharp]</sub> - Single-node query processor for temporal and streaming data from Microsoft Research.
* [AthenaX](https://github.com/uber-archive/AthenaX) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Uber's retired SQL-based streaming analytics platform.
* [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Stream and batch processing engine whose development moved into Hazelcast Platform.
* [Esper](https://github.com/espertechinc/esper) ⭐ 875 | 🐛 16 | 🌐 Java | 📅 2024-04-26 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Complex event processing, Streaming SQL, and event series analysis engine.
* [Apache Samza](https://github.com/apache/samza) ⭐ 846 | 🐛 43 | 🌐 Java | 📅 2026-08-20 <sub>![Java/Scala][language-java-scala]</sub> - Distributed stream processing framework built on Apache Kafka with standalone and YARN deployment options.
* [Gazette](https://github.com/gazette/core) ⭐ 795 | 🐛 21 | 🌐 Go | 📅 2026-07-25 <sub>![Go][language-go]</sub> - Cloud-storage-backed streaming infrastructure that combines SQL, batch, and millisecond-latency stream processing.
* [Gearpump](https://github.com/gearpump/gearpump) ⭐ 755 | 🐛 2 | 🌐 Scala | 📅 2026-08-18 <sub>![Scala][language-scala]</sub> - Lightweight real-time distributed streaming engine built on Akka.
* [Apache StreamPipes](https://github.com/apache/streampipes) ⭐ 739 | 🐛 60 | 🌐 Java | 📅 2026-08-23 <sub>![Java/Python/TypeScript][language-java-python-typescript]</sub> - Self-service industrial IoT platform for connecting, analyzing, and exploring data streams.
* [HStreamDB](https://github.com/hstreamdb/hstream) ⭐ 722 | 🐛 11 | 🌐 Haskell | 📅 2024-12-26 <sub>![Haskell][language-haskell]</sub> - Cloud-native streaming database for IoT data storage and real-time processing.
* [Apache Apex](https://github.com/apache/apex-core) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Unified platform for big data stream and batch processing.
* [ksqlDB](https://github.com/confluentinc/ksql) ⭐ 315 | 🐛 1,320 | 🌐 Java | 📅 2026-08-23 <sub>![Java][language-java]</sub> - Source-available database purpose-built for stream processing applications.
* [Tigon](https://github.com/cdapio/tigon) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![C++/Java][language-cpp-java]</sub> - High-throughput real-time stream processing framework built on Hadoop and HBase.
* [Squall](https://github.com/epfldata/squall) ⭐ 274 | 🐛 3 | 🌐 Java | 📅 2017-05-18 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Online SQL query processing engine built on Apache Storm.
* [SensorBee](https://github.com/sensorbee/sensorbee) ⭐ 231 | 🐛 39 | 🌐 Go | 📅 2019-11-04 <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Discontinued lightweight stream processing engine for IoT.
* [Wingfoil](https://github.com/wingfoil-io/wingfoil) ⭐ 213 | 🐛 32 | 🌐 Rust | 📅 2026-08-23 <sub>![Rust/Python/TypeScript][language-rust-python-typescript]</sub> - Graph-based stream processing engine for latency-critical systems.
* [mupd8 (Muppet)](https://github.com/walmartlabs/mupd8) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Scala/Java][language-scala-java]</sub> - MapReduce-style framework for processing fast-moving data streams.
* [hailstorm](https://github.com/hailstorm-hs/hailstorm) ⭐ 94 | 🐛 1 | 🌐 Haskell | 📅 2014-06-11 <sub>![Archived][archived-badge]</sub> <sub>![Haskell][language-haskell]</sub> - Distributed stream processing with exactly-once semantics based on Storm.
* [NebulaStream](https://github.com/nebulastream/nebulastream) ⭐ 94 | 🐛 254 | 🌐 C++ | 📅 2026-08-23 <sub>![C++][language-cpp]</sub> - Data management system for cloud-edge-sensor environments.
* [LightSaber](https://github.com/lsds/LightSaber) ⭐ 74 | 🐛 0 | 🌐 C++ | 📅 2021-10-20 <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Multi-core stream processing engine using code generation for window aggregation.
* [Scramjet Cloud Platform](https://github.com/scramjetorg/transform-hub) ⭐ 71 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-09 <sub>![TypeScript/Python][language-typescript-python]</sub> - Distributed runtime for running and managing data processing programs on edge, server, and cloud infrastructure.
* [SABER](https://github.com/lsds/Saber) ⭐ 44 | 🐛 10 | 🌐 Java | 📅 2022-11-16 <sub>![Archived][archived-badge]</sub> <sub>![Java/C][language-java-c]</sub> - Window-based hybrid CPU/GPU stream processing engine.
* [S4](https://github.com/apache/incubator-retired-s4) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed platform for processing continuous unbounded data streams.
* [LaminarDB](https://github.com/laminardb/laminardb) ⭐ 42 | 🐛 24 | 🌐 Rust | 📅 2026-08-23 <sub>![Rust][language-rust]</sub> - Embeddable streaming SQL engine built on Apache Arrow and DataFusion.
* [Maki Nage](https://github.com/maki-nage/makinage) ⭐ 42 | 🐛 8 | 🌐 Python | 📅 2022-04-24 <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Stream processing framework for data scientists based on Kafka and ReactiveX.
* [SPQR](https://github.com/ottogroup/SPQR) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Dynamic framework for processing high-volume data streams through pipelines.
* [Teknek](https://github.com/edwardcapriolo/teknek-core) ⭐ 10 | 🐛 1 | 🌐 Java | 📅 2015-12-15 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Stream processing platform with the interactive Stream Operator Language shell.
* [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2017-07-12 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Storm-based continuous query language for real-time computation.
* [Materialize](https://materialize.com) <sub>![Rust][language-rust]</sub> - Incremental SQL engine for maintaining continuously updated views over changing data.

### Libraries, SDKs, and Programming Models

* [MediaPipe](https://github.com/google-ai-edge/mediapipe) ⭐ 36,694 | 🐛 550 | 🌐 C++ | 📅 2026-08-21 <sub>![C++/Python/Java/TypeScript][language-cpp-python-java-typescript]</sub> - Cross-platform, customizable ML solutions for live and streaming media.
* [Apache Kafka Streams](https://github.com/apache/kafka) ⭐ 33,597 | 🐛 515 | 🌐 Java | 📅 2026-08-23 <sub>![Java][language-java]</sub> - Stream processing library included with Apache Kafka.
* [Akka](https://github.com/akka/akka-core) ⭐ 13,276 | 🐛 906 | 🌐 Scala | 📅 2026-08-21 <sub>![Scala/Java][language-scala-java]</sub> - Toolkit and runtime for concurrent, distributed, resilient applications on the JVM.
* [Akka Streams](https://github.com/akka/akka-core) ⭐ 13,276 | 🐛 906 | 🌐 Scala | 📅 2026-08-21 <sub>![Scala/Java][language-scala-java]</sub> - Reactive Streams implementation built on Akka actors.
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,647 | 🐛 3,969 | 🌐 Java | 📅 2026-08-23 <sub>![Java/Python/Go][language-java-python-go]</sub> - Unified programming model and language-specific SDKs for batch and streaming data processing.
* [Faust](https://github.com/robinhood/faust) ⭐ 6,824 | 🐛 279 | 🌐 Python | 📅 2024-07-27 <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Deprecated Python stream processing library inspired by Kafka Streams.
* [River](https://github.com/online-ml/river) ⭐ 5,922 | 🐛 70 | 🌐 Python | 📅 2026-08-21 <sub>![Python][language-python]</sub> - Online machine learning library for Python.
* [FastStream](https://github.com/ag2ai/faststream) ⭐ 5,314 | 🐛 103 | 🌐 Python | 📅 2026-08-22 <sub>![Python][language-python]</sub> - Asynchronous framework for building event-driven applications with Kafka, RabbitMQ, NATS, Redis, and MQTT.
* [FS2](https://github.com/typelevel/fs2) ⭐ 2,450 | 🐛 153 | 🌐 Scala | 📅 2026-08-20 <sub>![Scala][language-scala]</sub> - Compositional streaming I/O library for Scala.
* [Summingbird](https://github.com/twitter/summingbird) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Retired library for expressing streaming MapReduce computations over Storm and Scalding.
* [Monix](https://github.com/monix/monix) ⭐ 1,931 | 🐛 87 | 🌐 Scala | 📅 2026-08-23 <sub>![Scala][language-scala]</sub> - High-performance Scala and Scala.js library for asynchronous and event-based programs.
* [Pulsar](https://github.com/quantmind/pulsar) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Actor-based event-driven concurrency framework for Python.
* [Apache Pekko](https://github.com/apache/pekko) ⭐ 1,625 | 🐛 160 | 🌐 Scala | 📅 2026-08-21 <sub>![Scala/Java][language-scala-java]</sub> - Open-source toolkit for concurrent, distributed, resilient applications, forked from Akka 2.6.
* [Quix Streams](https://github.com/quixio/quix-streams) ⭐ 1,568 | 🐛 30 | 🌐 Python | 📅 2026-08-14 <sub>![Python][language-python]</sub> - Python framework for real-time data engineering, analytics, and machine learning on Apache Kafka.
* [Streamparse](https://github.com/pystorm/streamparse) ⭐ 1,505 | 🐛 61 | 🌐 Python | 📅 2026-04-22 <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Python API, command-line tools, and topology DSL for Apache Storm.
* [Streamz](https://github.com/python-streamz/streamz) ⭐ 1,303 | 🐛 121 | 🌐 Python | 📅 2026-04-07 <sub>![Python][language-python]</sub> - Library for building continuous data pipelines with branching, joining, flow control, and back pressure.
* [Apache StormCrawler](https://github.com/apache/stormcrawler) ⭐ 992 | 🐛 22 | 🌐 Java | 📅 2026-08-17 <sub>![Java][language-java]</sub> - Scalable web crawler SDK based on Apache Storm.
* [DataSketches](https://github.com/apache/datasketches-java) ⭐ 959 | 🐛 10 | 🌐 Java | 📅 2026-08-13 <sub>![Java][language-java]</sub> - Apache library of stochastic streaming algorithms known as sketches.
* [Jubatus](https://github.com/jubatus/jubatus) ⭐ 707 | 🐛 4 | 🌐 C++ | 📅 2019-05-16 <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Distributed processing framework and library for online machine learning.
* [Streamiz.Kafka.Net](https://github.com/LGouellec/streamiz) ⭐ 543 | 🐛 29 | 🌐 C# | 📅 2026-07-23 <sub>![C#][language-csharp]</sub> - .NET stream processing library for Apache Kafka.
* [streamDM](https://github.com/huawei-noah/streamDM) ⭐ 496 | 🐛 4 | 🌐 Scala | 📅 2023-04-16 <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Huawei library for mining data streams with Spark Streaming.
* [Tributary](https://github.com/1kbgz/tributary) ⭐ 466 | 🐛 9 | 🌐 Python | 📅 2026-06-23 <sub>![Python][language-python]</sub> - Python library for constructing synchronous, reactive, and lazy dataflow graphs.
* [trident-ml](https://github.com/pmerienne/trident-ml) ⭐ 383 | 🐛 3 | 🌐 Java | 📅 2023-12-16 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Online machine learning library based on Apache Storm Trident.
* [Apache SAMOA](https://github.com/apache/incubator-samoa) ⭐ 251 | 🐛 17 | 🌐 Java | 📅 2026-05-15 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed streaming machine learning framework.
* [Apache Edgent](https://github.com/apache/incubator-retired-edgent) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired programming model and runtime for streaming analytics on gateways and edge devices.
* [StormCV](https://github.com/sensorstorm/StormCV) ⭐ 174 | 🐛 3 | 🌐 Java | 📅 2016-12-20 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Computer vision operations and data models for Apache Storm.
* [Swave](https://github.com/sirthias/swave) ⭐ 173 | 🐛 8 | 🌐 Scala | 📅 2018-06-18 <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Lightweight Reactive Streams infrastructure toolkit for Scala.
* [Numalogic](https://github.com/numaproj/numalogic) ⭐ 172 | 🐛 52 | 🌐 Python | 📅 2024-10-15 <sub>![Python][language-python]</sub> - Collection of machine learning models and tools for anomaly detection and forecasting on operational time-series data.
* [Daggy](https://github.com/synacker/daggy) ⭐ 165 | 🐛 7 | 🌐 C++ | 📅 2026-07-26 <sub>![C++][language-cpp]</sub> - Utility and developer library for aggregating and capturing data streams.
* [CapyMOA](https://github.com/adaptive-machine-learning/CapyMOA) ⭐ 143 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-08-20 <sub>![Python/Java][language-python-java]</sub> - Machine learning library for data streams with a Python API and MOA backend.
* [Yurita](https://github.com/paypal/yurita) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - PayPal anomaly detection framework built on Spark Structured Streaming.
* [samza-luwak](https://github.com/romseygeek/samza-luwak) ⭐ 100 | 🐛 0 | 🌐 Java | 📅 2014-11-10 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Integration of Apache Samza with the Luwak stored-query engine for full-text stream search.
* [WindFlow](https://github.com/ParaGroup/WindFlow) ⭐ 88 | 🐛 11 | 🌐 C++ | 📅 2026-04-25 <sub>![C++][language-cpp]</sub> - Data stream processing parallel library for multi-core CPUs and GPUs.
* [coast](https://github.com/bkirwi/coast) ⭐ 60 | 🐛 5 | 🌐 Scala | 📅 2016-08-27 <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - DSL that builds exactly-once dataflow graphs on top of Apache Samza.
* [Stream Ops](https://github.com/nanosai/stream-ops-java) ⭐ 50 | 🐛 4 | 🌐 Java | 📅 2019-10-20 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Embeddable data streaming engine and stream processing API for Java.
* [Scramjet TypeScript](https://github.com/scramjetorg/framework-js) ⭐ 41 | 🐛 10 | 🌐 TypeScript | 📅 2022-04-29 <sub>![Archived][archived-badge]</sub> <sub>![TypeScript][language-typescript]</sub> - Reactive stream programming framework for asynchronous JavaScript and TypeScript applications.
* [Scramjet Python](https://github.com/scramjetorg/framework-python) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2023-10-24 <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Reactive stream programming framework for Python.
* [Kzmlabs StateFun Actors](https://github.com/kzmlabs/flink-statefun) ⭐ 13 | 🐛 17 | 🌐 Java | 📅 2026-08-16 <sub>![Java][language-java]</sub> - Stateful actors on Apache Flink 2.x with durable per-key state, exactly-once messaging, and Kafka and Kinesis I/O.
* [Scramjet C++](https://github.com/scramjetorg/framework-cpp) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2022-09-09 <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Reactive stream programming framework for C++.

### Data Integration and Pipelines

* [Pathway](https://github.com/pathwaycom/pathway) ⭐ 62,400 | 🐛 35 | 🌐 Python | 📅 2026-08-23 <sub>![Python/Rust][language-python-rust]</sub> - Python ETL framework for stream processing, real-time analytics, and AI data pipelines.
* [CocoIndex](https://github.com/cocoindex-io/cocoindex) ⭐ 11,390 | 🐛 73 | 🌐 Rust | 📅 2026-08-18 <sub>![Rust/Python][language-rust-python]</sub> - Incremental data transformation engine for continuously updated AI and agent workloads.
* [Redpanda Connect](https://github.com/redpanda-data/connect) ⭐ 8,731 | 🐛 322 | 🌐 Go | 📅 2026-08-21 <sub>![Go][language-go]</sub> - Declarative stream processor for moving, enriching, transforming, and filtering data between sources and sinks.
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,475 | 🐛 53 | 🌐 Go | 📅 2026-08-21 <sub>![Go][language-go]</sub> - Developer-focused customer data platform for event streaming and cloud-to-warehouse data pipelines.
* [inGestr](https://github.com/bruin-data/ingestr) ⭐ 3,857 | 🐛 16 | 🌐 Go | 📅 2026-08-21 <sub>![Go/Python][language-go-python]</sub> - Command-line application and Python SDK for copying data between databases, SaaS applications, and data warehouses.
* [Databus](https://github.com/linkedin/databus) ⭐ 3,679 | 🐛 41 | 🌐 Java | 📅 2023-09-28 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - LinkedIn source-agnostic distributed change data capture system.
* [Apache Flume](https://github.com/apache/logging-flume) ⭐ 2,565 | 🐛 80 | 🌐 Java | 📅 2026-08-21 <sub>![Java][language-java]</sub> - Distributed service for collecting, aggregating, and moving large amounts of log-like data.
* [Bruin](https://github.com/bruin-data/bruin) ⭐ 1,673 | 🐛 36 | 🌐 Go | 📅 2026-08-22 <sub>![Go][language-go]</sub> - End-to-end data pipeline tool combining ingestion, SQL and Python transformations, and data quality checks.
* [Brooklin](https://github.com/linkedin/Brooklin) ⭐ 965 | 🐛 36 | 🌐 Java | 📅 2026-08-19 <sub>![Java][language-java]</sub> - Distributed system for reliable nearline data streaming between heterogeneous systems at scale.
* [Camus](https://github.com/LinkedInAttic/camus) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - LinkedIn's retired, previous-generation Kafka-to-HDFS pipeline.
* [Suro](https://github.com/Netflix/suro) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Netflix data pipeline for collecting, aggregating, and dispatching application events.
* [faucet-stream](https://github.com/faucet-hq/faucet-stream) ⭐ 8 | 🐛 11 | 🌐 Rust | 📅 2026-08-23 <sub>![Rust][language-rust]</sub> - Config-driven platform and embeddable library for ETL, CDC, and streaming data movement.
* [yasdb](https://github.com/JayJamieson/yasdb) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-08-13 <sub>![Go][language-go]</sub> - Durable Streams protocol server backed by SlateDB object storage, with offset-based catch-up reads and SSE or long-poll tailing.

### Applications and Tools

* [StreamAlert](https://github.com/airbnb/streamalert) ⭐ 2,889 | 🐛 90 | 🌐 Python | 📅 2023-10-23 <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Airbnb serverless framework for real-time security log analysis and alerting.
* [Zilla](https://github.com/aklivity/zilla) ⭐ 1,706 | 🐛 219 | 🌐 Java | 📅 2026-08-22 <sub>![Java][language-java]</sub> - Multi-protocol gateway for connecting applications, APIs, agents, and devices to event streams.
* [Turbine](https://github.com/Netflix/Turbine) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Netflix tool for aggregating Server-Sent Event JSON streams.
* [Nussknacker](https://github.com/TouK/nussknacker) ⭐ 743 | 🐛 52 | 🌐 Scala | 📅 2026-08-20 <sub>![Scala][language-scala]</sub> - Visual tool for defining and running real-time decision algorithms.
* [Streamdal](https://github.com/streamdal/streamdal) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![TypeScript][language-typescript]</sub> - Code-native data privacy controls for detecting PII in application data flows.
* [Substation](https://github.com/brexhq/substation) ⭐ 403 | 🐛 3 | 🌐 Go | 📅 2026-01-20 <sub>![Go][language-go]</sub> - Toolkit for routing, normalizing, and enriching security event and audit logs.
* [StreamFlow](https://github.com/lmco/streamflow) ⭐ 257 | 🐛 35 | 🌐 Java | 📅 2024-12-16 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Tool for building and monitoring stream processing workflows.
* [Streamline](https://github.com/hortonworks/streamline) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Hortonworks visual stream analytics framework built around engines such as Apache Storm.
* [beava](https://github.com/beava-dev/beava) ⭐ 138 | 🐛 38 | 🌐 Rust | 📅 2026-05-30 <sub>![Rust/Python][language-rust-python]</sub> - Single-binary feature server for querying fresh per-entity counters and aggregates without a message broker.
* [straw](https://github.com/rwalk/straw) ⭐ 103 | 🐛 2 | 🌐 Python | 📅 2016-03-09 <sub>![Archived][archived-badge]</sub> <sub>![Python/Java][language-python-java]</sub> - Platform for real-time streaming search.
* [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) ⭐ 85 | 🐛 4 | 🌐 Python | 📅 2025-09-04 <sub>![Python][language-python]</sub> - Web application for setting up and evaluating contextual multi-armed bandit experiments.
* [Eventum](https://github.com/eventum-generator/eventum) ⭐ 63 | 🐛 4 | 🌐 Python | 📅 2026-08-21 <sub>![Python/TypeScript][language-python-typescript]</sub> - Data generation platform for producing synthetic event streams.
* [javactrl-kafka](https://github.com/javactrl/javactrl-kafka) ⭐ 18 | 🐛 5 | 🌐 Java | 📅 2025-04-30 <sub>![Java][language-java]</sub> - Code-first distributed workflow engine for microservice orchestration and business process automation.

### Managed and Closed Source

* [Amazon Kinesis Data Streams](https://aws.amazon.com/kinesis/data-streams/) - Fully managed service for ingesting and processing real-time data streams on AWS.
* [Azure Stream Analytics](https://azure.microsoft.com/en-us/products/stream-analytics) <sub>![SQL][language-sql]</sub> - Fully managed service for serverless real-time analytics in the cloud and at the edge.
* [Concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Historical distributed stream processing framework built on Apache Mesos.
* [Google Cloud Dataflow](https://cloud.google.com/dataflow/) <sub>![Java/Python/Go][language-java-python-go]</sub> - Fully managed service for running Apache Beam batch and streaming pipelines.
* [IBM Streams](https://www.ibm.com/support/pages/ibm-streams-life-cycle-guidance) <sub>![Archived][archived-badge]</sub> <sub>![Python/Java/Scala][language-python-java-scala]</sub> - Discontinued proprietary platform for distributed stream processing and real-time analytics.
* [NVIDIA DeepStream SDK](https://developer.nvidia.com/deepstream-sdk) <sub>![C/C++/Python][language-c-cpp-python]</sub> - GStreamer-based toolkit with open-source components and proprietary NVIDIA libraries for real-time AI streaming analytics and multi-sensor processing.

### Benchmarks

* [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) ⭐ 648 | 🐛 25 | 🌐 Jupyter Notebook | 📅 2023-12-17 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Benchmarks for low-latency stream processing systems including Storm, Spark, and Flink.
* [Flotilla](https://github.com/tylertreat/Flotilla) ⚠️ Archived <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Automated message queue orchestration for scaled-up benchmarking.
* [storm-perf-test](https://github.com/yahoo/storm-perf-test) ⭐ 75 | 🐛 2 | 🌐 Java | 📅 2023-03-21 <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Apache Storm performance and stress test.

### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) by Tyler Akidau.
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](https://arxiv.org/abs/1708.02621)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) by Josh Fischer & Ning Wang
5. [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) by Reuven Lax, Slava Chernyak, and Tyler Akidau
6. [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) by Bas P. Harenslak and Julian Rutger de Ruiter
7. [MillWheel: Fault-Tolerant Stream Processing at Internet Scale](https://research.google/pubs/millwheel-fault-tolerant-stream-processing-at-internet-scale/)

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

[archived-badge]: https://img.shields.io/badge/status-archived-lightgrey

[language-c]: https://img.shields.io/badge/language-C-blue

[language-c-cpp-python]: https://img.shields.io/badge/language-C%2FC%2B%2B%2FPython-blue

[language-csharp]: https://img.shields.io/badge/language-C%23-blue

[language-cpp]: https://img.shields.io/badge/language-C%2B%2B-blue

[language-cpp-java]: https://img.shields.io/badge/language-C%2B%2B%2FJava-blue

[language-cpp-python-java-typescript]: https://img.shields.io/badge/language-C%2B%2B%2FPython%2FJava%2FTypeScript-blue

[language-clojure]: https://img.shields.io/badge/language-Clojure-blue

[language-go]: https://img.shields.io/badge/language-Go-blue

[language-go-python]: https://img.shields.io/badge/language-Go%2FPython-blue

[language-haskell]: https://img.shields.io/badge/language-Haskell-blue

[language-java]: https://img.shields.io/badge/language-Java-blue

[language-java-c]: https://img.shields.io/badge/language-Java%2FC-blue

[language-java-cpp]: https://img.shields.io/badge/language-Java%2FC%2B%2B-blue

[language-java-python-go]: https://img.shields.io/badge/language-Java%2FPython%2FGo-blue

[language-java-python-typescript]: https://img.shields.io/badge/language-Java%2FPython%2FTypeScript-blue

[language-java-scala]: https://img.shields.io/badge/language-Java%2FScala-blue

[language-pony]: https://img.shields.io/badge/language-Pony-blue

[language-python]: https://img.shields.io/badge/language-Python-blue

[language-python-java]: https://img.shields.io/badge/language-Python%2FJava-blue

[language-python-java-scala]: https://img.shields.io/badge/language-Python%2FJava%2FScala-blue

[language-python-rust]: https://img.shields.io/badge/language-Python%2FRust-blue

[language-python-typescript]: https://img.shields.io/badge/language-Python%2FTypeScript-blue

[language-rust]: https://img.shields.io/badge/language-Rust-blue

[language-rust-go-typescript]: https://img.shields.io/badge/language-Rust%2FGo%2FTypeScript-blue

[language-rust-python]: https://img.shields.io/badge/language-Rust%2FPython-blue

[language-rust-python-typescript]: https://img.shields.io/badge/language-Rust%2FPython%2FTypeScript-blue

[language-rust-wasm]: https://img.shields.io/badge/language-Rust%2FWASM-blue

[language-scala]: https://img.shields.io/badge/language-Scala-blue

[language-scala-java]: https://img.shields.io/badge/language-Scala%2FJava-blue

[language-scala-java-python-r]: https://img.shields.io/badge/language-Scala%2FJava%2FPython%2FR-blue

[language-sql]: https://img.shields.io/badge/language-SQL-blue

[language-typescript]: https://img.shields.io/badge/language-TypeScript-blue

[language-typescript-python]: https://img.shields.io/badge/language-TypeScript%2FPython-blue

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
