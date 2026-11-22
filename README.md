### Hi, I'm Dart Mon

Data engineer with 4+ years of experience. I build the data platforms other teams rely on: streaming, lakehouse, and real-time analytics. I contribute to **ClickHouse** and **Apache Flink**.

#### Open source

**ClickHouse** · [all my PRs](https://github.com/ClickHouse/ClickHouse/pulls?q=is%3Apr+author%3AShadow88Mornach)

- [#132254](https://github.com/ClickHouse/ClickHouse/pull/132254) S3Queue: remove the empty per-database Keeper node on `DROP` (bug fix)
- [#133488](https://github.com/ClickHouse/ClickHouse/pull/133488) Report legacy `s3queue_`-prefixed settings as changed in `system.s3_queue_settings` (bug fix)
- [#132255](https://github.com/ClickHouse/ClickHouse/pull/132255) Add a `Settings` column to `system.query_views_log`
- [#132218](https://github.com/ClickHouse/ClickHouse/pull/132218) Docs: how often the Kafka engine flushes to materialized views (merged)
- [#123848](https://github.com/ClickHouse/ClickHouse/pull/123848) Docs: macro expansion in Kafka engine settings (merged)

#### What I've built

- **Fintech data platform**: designed a 300-node platform; my team and I migrated 3 PB onto it with zero downtime.
- **Credit and fraud scoring**: ran the daily pipeline that scores 70M subscriptions a day for lending partners, and rebuilt its serving layer on ClickHouse, with model versioning and data-quality checks before results go live.
- **Analytics at scale**: ran the analytics database for a 20M-user product and cut query latency in half.
- **ML pipelines**: URL topic classification on 300M rows, with Airflow pipelines, auto-labeling and automatic retraining tracked in MLflow.
- **Now**: building a streaming data platform on AWS with Flink and an Iceberg lakehouse on S3 (Glue, Terraform).

#### Stack

ClickHouse · Apache Flink · Kafka · Spark · Apache Iceberg · Airflow · MLflow · AWS (S3, Glue) · Terraform · Python · SQL · Java · C++
