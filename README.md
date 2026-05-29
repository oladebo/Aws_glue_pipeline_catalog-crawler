
## AWS Glue Serverless Data Pipeline (Crawler & Data Catalog)

## Overview

This project demonstrates a fully serverless data pipeline using AWS Glue, Amazon S3, and AWS Glue Data Catalog. The solution automates data discovery, schema inference, and metadata management using AWS Glue Crawlers.

### Architecture

![image alt](https://github.com/oladebo/Aws_glue_pipeline_catalog-crawler/blob/0c23967117d6a1feb82479f9d9c5dca24868ca98/Screen%20Shot%202026-05-29%20at%2014.11.48.png)


Data is stored in Amazon S3, where AWS Glue Crawlers scan the datasets, infer schema, and automatically create tables in the Glue Data Catalog. The cataloged data can then be queried using analytics services such as Amazon Athena.

#### Key Features
- Serverless data ingestion and processing
- Automated schema discovery using AWS Glue Crawlers
- Centralized metadata storage in AWS Glue Data Catalog
- Integration with Amazon S3 for scalable storage
- Secure access management using AWS IAM
  
#### Workflow
- Upload raw datasets to Amazon S3
- Configure AWS Glue Crawler with IAM role permissions
- Crawler scans data and infers schema
- Metadata is stored in AWS Glue Data Catalog
- Data becomes queryable using analytics tools
  
#### Benefits
- Eliminates manual schema creation
- Improves data discovery and governance
- Reduces ETL development effort
- Enables scalable and automated data pipelines
- Tools & Services Used
  
AWS Glue
Amazon S3
AWS Glue Data Catalog
AWS IAM
Amazon Athena, Redshift or Glue (optional for querying)

#### Conclusion

This project demonstrates how AWS serverless services can be combined to build an efficient, automated, and scalable data pipeline for modern data engineering workflows.


https://drive.google.com/file/d/1tOHrOhXXmJK8IEsLPLFEHZb0IOhdKu1a/view?usp=drive_link

Thanks

By Oladebo Ayanniyi
Cloud Data Engineer
