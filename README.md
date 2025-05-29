# 2023-build-search-index-flink-elasticsearch

Build a Lightning Fast Search Index Using Redpanda, Flink, and Elasticsearch
目录结构如下“”

```shell
 tree -L 2 ./
./
├── camel-elasticsearch-index-sink-kafka-connector-4.10.3-package.tar.gz
├── configuration
│   ├── connect.properties
│   ├── elasticsearch-sink-connector.properties
│   └── kafka_2.13-3.7.2.tgz
├── data
│   └── sql
├── docker-compose.yml
├── Dockerfile
├── docs
│   └── examples
├── flink-conf
│   ├── job
│   └── task
├── kafka_2.13-3.7.2
│   ├── bin
│   ├── config
│   ├── libs
│   ├── LICENSE
│   ├── licenses
│   ├── logs
│   ├── NOTICE
│   └── site-docs
├── plugins
│   └── camel-elasticsearch-index-sink-kafka-connector
├── producer.py
├── README.md
└── sql
    ├── useractivity_enriched.sql
    └── useractivity.sql

```
