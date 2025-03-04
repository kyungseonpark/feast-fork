Feast Python API Documentation
==============================


Feature Store
==================

.. automodule:: feast.feature_store
   :members:
   :undoc-members:
   :show-inheritance:

Config
==================

.. automodule:: feast.repo_config
    :members:
    :exclude-members: load_repo_config, FeastBaseModel

Data Source
==================

.. automodule:: feast.data_source
    :inherited-members:
    :members:
    :exclude-members: KafkaOptions, KafkaSource, KinesisOptions, KinesisSource, PushSource, RequestSource, RequestDataSource

Request Source
------------------

.. automodule:: feast.data_source
    :members: RequestSource

Push Source
------------------

.. automodule:: feast.data_source
    :members: PushSource

BigQuery Source
------------------

.. automodule:: feast.infra.offline_stores.bigquery_source
    :members:
    :exclude-members: BigQueryOptions

Redshift Source
------------------

.. automodule:: feast.infra.offline_stores.redshift_source
    :members:
    :exclude-members: RedshiftOptions

Snowflake Source
------------------

.. automodule:: feast.infra.offline_stores.snowflake_source
    :members:
    :exclude-members: SnowflakeOptions

Spark Source
------------------

.. automodule:: feast.infra.offline_stores.contrib.spark_offline_store.spark_source
    :members:
    :exclude-members: SparkOptions

Trino Source
------------------

.. automodule:: feast.infra.offline_stores.contrib.trino_offline_store.trino_source
    :members:
    :exclude-members: TrinoOptions

PostgreSQL Source
------------------

.. automodule:: feast.infra.offline_stores.contrib.postgres_offline_store.postgres_source
    :members:
    :exclude-members: PostgreSQLOptions

File Source
------------------

.. automodule:: feast.infra.offline_stores.file_source
    :members:
    :exclude-members: FileOptions

Entity
==================

.. automodule:: feast.entity
    :inherited-members:
    :members:

Feature View
==================

.. automodule:: feast.base_feature_view
    :members:

Feature View
----------------------

.. automodule:: feast.feature_view
    :members:

On Demand Feature View
----------------------

.. automodule:: feast.on_demand_feature_view
    :members:

Stream Feature View
----------------------

.. automodule:: feast.stream_feature_view
    :members:

Feature
==================

.. automodule:: feast.feature
    :inherited-members:
    :members:

Feature Service
==================

.. automodule:: feast.feature_service
    :inherited-members:
    :members:

Registry
==================

.. automodule:: feast.infra.registry.base_registry
    :inherited-members:
    :members:

Registry
----------------------

.. automodule:: feast.infra.registry.registry
    :inherited-members:
    :members:

SQL Registry
----------------------

.. automodule:: feast.infra.registry.sql
    :inherited-members:
    :members:

Registry Store
==================

.. automodule:: feast.infra.registry.registry_store
    :inherited-members:
    :members:
    :exclude-members: NoopRegistryStore

File Registry Store
-----------------------

.. automodule:: feast.infra.registry.file
    :members:
    :noindex:

GCS Registry Store
-----------------------

.. automodule:: feast.infra.registry.gcs
    :members:
    :noindex:

S3 Registry Store
-----------------------

.. automodule:: feast.infra.registry.s3
    :members:
    :noindex:

PostgreSQL Registry Store
-----------------------

.. automodule:: feast.infra.registry.contrib.postgres.postgres_registry_store
    :members:
    :noindex:

Provider
==================

.. automodule:: feast.infra.provider
    :inherited-members:
    :members:

Passthrough Provider
--------------------

.. automodule:: feast.infra.passthrough_provider
    :members:

Local Provider
------------------

.. automodule:: feast.infra.local
    :members:

GCP Provider
------------------

.. automodule:: feast.infra.gcp
    :members:

AWS Provider
------------------

.. automodule:: feast.infra.aws
    :members:

Offline Store
==================

.. automodule:: feast.infra.offline_stores.offline_store
    :members:

File Offline Store
------------------

.. automodule:: feast.infra.offline_stores.file
    :members:

BigQuery Offline Store
----------------------

.. automodule:: feast.infra.offline_stores.bigquery
    :members:

Redshift Offline Store
----------------------

.. automodule:: feast.infra.offline_stores.redshift
    :members:

Snowflake Offline Store
-----------------------

.. automodule:: feast.infra.offline_stores.snowflake
    :members:

Spark Offline Store
-------------------

.. automodule:: feast.infra.offline_stores.contrib.spark_offline_store.spark
    :members:

Trino Offline Store
-------------------

.. automodule:: feast.infra.offline_stores.contrib.trino_offline_store.trino
    :members:

PostgreSQL Offline Store
------------------------

.. automodule:: feast.infra.offline_stores.contrib.postgres_offline_store.postgres
    :members:


Online Store
==================

.. automodule:: feast.infra.online_stores.online_store
    :inherited-members:
    :members:

Sqlite Online Store
-------------------

.. automodule:: feast.infra.online_stores.sqlite
    :members:
    :noindex:

Datastore Online Store
----------------------

.. automodule:: feast.infra.online_stores.datastore
    :members:
    :noindex:

DynamoDB Online Store
---------------------

.. automodule:: feast.infra.online_stores.dynamodb
    :members:
    :noindex:

Redis Online Store
------------------

.. automodule:: feast.infra.online_stores.redis
    :members:
    :noindex:

PostgreSQL Online Store
-----------------------

.. automodule:: feast.infra.online_stores.contrib.postgres
    :members:
    :noindex:

HBase Online Store
-----------------------

.. automodule:: feast.infra.online_stores.contrib.hbase_online_store.hbase
    :members:
    :noindex:

Cassandra Online Store
-----------------------

.. automodule:: feast.infra.online_stores.contrib.cassandra_online_store.cassandra_online_store
    :members:
    :noindex:


Batch Materialization Engine
============================

.. automodule:: feast.infra.materialization
    :members: BatchMaterializationEngine, MaterializationJob, MaterializationTask

Local Engine
------------
.. autoclass:: feast.infra.materialization.LocalMaterializationEngine
    :members:
    :noindex:

(Alpha) Lambda Based Engine
---------------------------

.. automodule:: feast.infra.materialization.lambda.lambda_engine
    :members:
    :noindex:


Bytewax Engine
---------------------------

.. automodule:: feast.infra.materialization.contrib.bytewax
    :members:
    :noindex:
