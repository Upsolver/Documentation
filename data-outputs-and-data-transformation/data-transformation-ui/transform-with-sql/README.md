---
description: This page provides an overview of the Transform with SQL feature in Upsolver.
---

# Transform with SQL

## Transform with SQL Architecture and Components

![alt\_text](https://docs.upsolver.com/Content/Resources/MarkdownConversion/UpSQL/images/SQL-main0.png)

Transform with SQL provides an easy to use and powerful SQL interface for data ingestion, integration, and transformation when creating Upsolver outputs without the need to write code in a programming language.

Transform with SQL in the Upsolver UI is based on ANSI SQL so it is easy and intuitive to use for anyone with basic SQL knowledge. Users write regular SQL queries with extensions for streaming data use cases such as window aggregations, and the Upsolver engine continuously executes the queries.

Transform with SQL is used to ingest data, read data from various streaming sources and data lakes \(including Amazon S3, Amazon Kinesis Streams, and Apache Kafka\), and writing data to the desired target \(e.g. Amazon Athena, Amazon Redshift, ElasticSearch, and RDS\).

