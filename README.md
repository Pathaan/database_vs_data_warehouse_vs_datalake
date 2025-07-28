# database_vs_data_warehouse_vs_datalake
 
 | Feature       | Database                 | Data Warehouse               | Data Lake                        |
| ------------- | ------------------------ | ---------------------------- | -------------------------------- |
| Data Type     | Structured               | Structured / Semi-structured | Structured / Semi / Unstructured |
| Storage Cost  | Medium                   | High                         | Low                              |
| Query Speed   | Fast for transactions    | Fast for analytics           | Slower, unless optimized         |
| Processing    | OLTP                     | OLAP                         | ELT or Schema-on-Read            |
| Users         | Developers, Apps         | Analysts, BI Users           | Data Scientists, Engineers       |
| Schema        | Strict (schema-on-write) | Strict                       | Flexible (schema-on-read)        |
| Example Tools | MySQL, PostgreSQL        | Snowflake, BigQuery          | Hadoop, AWS S3, Databricks       |
