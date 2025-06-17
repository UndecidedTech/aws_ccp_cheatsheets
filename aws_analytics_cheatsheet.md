AWS Analytics Cheatsheet
2025-06-17

Services to Know:
* Amazon Athena
* Amazon EMR (Elastic Map Reduce)
* Amazon CloudSearch
* Amazon Opensearch Service
* Amazon Kinesis
* Amazon QuickSightmazon Kinesismazon Kinesis
* Amazon Data Pipeline
* AWS Glue
* AWS Lake Formation
* Amazon MSK


Most Likely To Appear on the AWS CCP Exam:
* Amazon Athena
* Amazon EMR (Elastic Map Reduce)
* AWS Glue
* Amazon Kinesis


| AWS Service     | Primary Use Case | When to Use                                                                                                                                                                                                                          |
|-----------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Amazon Athena   | Query            | Run Interactive queries against data directly in Amazon S3 without worrying about formatting data or managing infrastructure. Can use with other services such as Amazon Redshift.                                                   |
| Amazon Redshift | Data Warehouse   | Pull data from many sources, format and organize it, store it, and support complex, high speed queries that produce business reports                                                                                                 |
| Amazon EMR      | Data Processing  | Highly distributed processing frameworks such as Hadoop,  Spark, and Presto. Run a wide variety of scale-out data  processing tasks for applications such as machine learning, graph analytics, data transformation, streaming data. |
| AWS Glue        | ETL Service      | Transform and move data to various destinations. Used to prepare and load data for analytics. Data source can be S3, Redshift or another database. Glue Data Catalog can be queried by Athena, EMR, and RedShift Spectrum.           |


Amazon EMR (Elastic Map Reduce): web service that enables business, researchers, data analysts, and developers to easily and cost-effectively process vast amounts of data.
EMR utilizes a hadoop framework running on EC2 and S3
Most commonly used for log analysis, financial analysis, or extract, translate and loading (ETL) activities

    Hadoop -- distributed data processing engine, that supports data-intensive distributed applications running on large clusters of commodity hardware

    EMR is a good place to deploy Apache Spark, open source distributed processing used for big data workloads, which utilizes in-memory caching and optimized query execution

    You can also launch Presto clusters, distributed SQL query engine designed for fast analytic queries against large datasets

    With EMR you have access to the underlying OS (you can SSH in)

Amazon Athena: an interactive query service that makes it easy to analyze data in AWS S3 using standard SQL

    Its serverless, so there is not infra to manage, you pay only for the queries you run.

    Easy to use - point to data in S3, define the schema, and start querying using SQL

    Athena uses Presto for SQL support, and works with a variety of data sets

AWS Glue: fully managed, pay-as-you-go, ETL service that automates time consuming steps of data prep for analytics

    AWS Glue automatically discovers and profiles data via Glue Data Catalog, reccs and generates ETL code to transform your source data into target schemas.

    AWS Glue runs on a managed Spark environment to load your data into its destination.

    Use AWS Glue to discover properties of data, transform it, and prepare it for analytics.
    Glue can automatically discover structured and semi-structured data stored in data lakes on S3, or warehouses in Redshift, and various databases running on AWS.

    Glue is obviously, serverless.

Amazon Kinesis: makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information.

    Collection of services for processing streams of various data.

    Data is processed in “shards”.

    There are four types of Kinesis service, and these are detailed below.

    Video Streams, Data Streams, Data Firehose, and Data Analytics




