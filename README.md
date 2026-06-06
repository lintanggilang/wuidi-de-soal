# ⚡ AWS Data Engineer Associate (DEA-C01) — Simulasi Latihan Ujian

Kumpulan soal latihan untuk sertifikasi **AWS Certified Data Engineer — Associate (DEA-C01)** dalam format HTML interaktif.

🔗 **Akses langsung:** [https://lintanggilang.github.io/wuidi-de-soal/](https://lintanggilang.github.io/wuidi-de-soal/)

---

## 📊 Ringkasan

| Item | Jumlah |
|------|--------|
| Total Skills | 120 |
| Total Soal | 1.200 |
| Simulasi Ujian | 10 set (masing-masing 120 soal) |
| Domain | 4 |
| Format | HTML statis (tanpa backend) |

---

## 🎯 Tentang Ujian

| Parameter | Detail |
|-----------|--------|
| Kode Ujian | DEA-C01 |
| Jumlah Soal | 65 |
| Durasi | 170 menit |
| Passing Score | 720/1000 |
| Format | Pilihan ganda (satu jawaban benar) |

---

## 📚 Cakupan Materi

Soal-soal mencakup kompetensi berikut:

- Setup dan maintenance pipeline ETL (Extract, Transform, Load) dari ingestion hingga destination
- Penerapan konsep pemrograman tingkat tinggi yang language-agnostic sesuai kebutuhan pipeline
- Penggunaan Git untuk source control
- Penggunaan data lake untuk menyimpan data
- Konsep umum networking, storage, dan compute
- Konsep umum vector
- Penggunaan layanan AWS untuk menyelesaikan tasks pada exam guide
- Pemahaman layanan AWS untuk encryption, governance, protection, dan logging data dalam pipeline
- Kemampuan membandingkan layanan AWS dari segi cost, performance, dan functional differences
- Penyusunan dan eksekusi SQL queries pada layanan AWS
- Pemahaman cara menganalisis data, memverifikasi data quality, dan memastikan data consistency menggunakan layanan AWS

---

## 📋 Daftar Domain dan Skill

### Domain 1: Data Ingestion and Transformation (34%)

| Task | Skill | Deskripsi |
|------|-------|-----------|
| Task 1.1: Perform data ingestion | Skill 1.1.1 | Read data from streaming sources (Kinesis, MSK, DynamoDB Streams, DMS, Glue, Redshift) |
| Task 1.1: Perform data ingestion | Skill 1.1.2 | Read data from batch sources (S3, Glue, EMR, DMS, Redshift, Lambda, AppFlow) |
| Task 1.1: Perform data ingestion | Skill 1.1.3 | Implement appropriate configuration options for batch ingestion |
| Task 1.1: Perform data ingestion | Skill 1.1.4 | Consume data APIs |
| Task 1.1: Perform data ingestion | Skill 1.1.5 | Set up schedulers (EventBridge, Apache Airflow, time-based schedules) |
| Task 1.1: Perform data ingestion | Skill 1.1.6 | Set up event triggers (S3 Event Notifications, EventBridge) |
| Task 1.1: Perform data ingestion | Skill 1.1.7 | Call a Lambda function from Kinesis |
| Task 1.1: Perform data ingestion | Skill 1.1.8 | Create allowlists for IP addresses to allow connections to data sources |
| Task 1.1: Perform data ingestion | Skill 1.1.9 | Implement throttling and overcoming rate limits (DynamoDB, RDS, Kinesis) |
| Task 1.1: Perform data ingestion | Skill 1.1.10 | Manage fan-in and fan-out for streaming data distribution |
| Task 1.1: Perform data ingestion | Skill 1.1.11 | Describe replayability of data ingestion pipelines |
| Task 1.1: Perform data ingestion | Skill 1.1.12 | Define stateful and stateless data transactions |
| Task 1.2: Transform and process data | Skill 1.2.1 | Optimize container usage for performance (EKS, ECS) |
| Task 1.2: Transform and process data | Skill 1.2.2 | Connect to different data sources (JDBC, ODBC) |
| Task 1.2: Transform and process data | Skill 1.2.3 | Integrate data from multiple sources |
| Task 1.2: Transform and process data | Skill 1.2.4 | Optimize costs while processing data |
| Task 1.2: Transform and process data | Skill 1.2.5 | Implement data transformation services (EMR, Glue, Lambda, Redshift) |
| Task 1.2: Transform and process data | Skill 1.2.6 | Transform data between formats (CSV to Parquet) |
| Task 1.2: Transform and process data | Skill 1.2.7 | Troubleshoot and debug common transformation failures |
| Task 1.2: Transform and process data | Skill 1.2.8 | Create data APIs to make data available to other systems |
| Task 1.2: Transform and process data | Skill 1.2.9 | Define volume, velocity, and variety of data |
| Task 1.2: Transform and process data | Skill 1.2.10 | Integrate large language models (LLMs) for data processing |
| Task 1.3: Orchestrate data pipelines | Skill 1.3.1 | Use orchestration services for ETL workflows (Lambda, EventBridge, MWAA, Step Functions, Glue) |
| Task 1.3: Orchestrate data pipelines | Skill 1.3.2 | Build pipelines for performance, availability, scalability, resiliency |
| Task 1.3: Orchestrate data pipelines | Skill 1.3.3 | Implement and maintain serverless workflows |
| Task 1.3: Orchestrate data pipelines | Skill 1.3.4 | Use notification services to send alerts (SNS, SQS) |
| Task 1.4: Apply programming concepts | Skill 1.4.1 | Optimize code to reduce runtime |
| Task 1.4: Apply programming concepts | Skill 1.4.2 | Configure Lambda functions for concurrency and performance |
| Task 1.4: Apply programming concepts | Skill 1.4.3 | Use programming languages and frameworks (Python, SQL, Scala, Java) |
| Task 1.4: Apply programming concepts | Skill 1.4.4 | Use software engineering best practices (version control, testing, logging) |
| Task 1.4: Apply programming concepts | Skill 1.4.5 | Use Infrastructure as Code (IaC) to deploy solutions |
| Task 1.4: Apply programming concepts | Skill 1.4.6 | Use AWS SAM to package and deploy serverless pipelines |
| Task 1.4: Apply programming concepts | Skill 1.4.7 | Use and mount storage volumes from within Lambda |
| Task 1.4: Apply programming concepts | Skill 1.4.8 | Use IaC for repeatable resource deployment (CloudFormation, CDK) |
| Task 1.4: Apply programming concepts | Skill 1.4.9 | Describe CI/CD (implementation, testing, deployment) |
| Task 1.4: Apply programming concepts | Skill 1.4.10 | Define distributed computing |
| Task 1.4: Apply programming concepts | Skill 1.4.11 | Describe data structures and algorithms (graph, tree) |

### Domain 2: Data Store Management (26%)

| Task | Skill | Deskripsi |
|------|-------|-----------|
| Task 2.1: Choose a data store | Skill 2.1.1 | Implement storage services for cost and performance (Redshift, EMR, RDS, DynamoDB, Kinesis, MSK) |
| Task 2.1: Choose a data store | Skill 2.1.2 | Configure storage services for access patterns |
| Task 2.1: Choose a data store | Skill 2.1.3 | Apply storage services to use cases (HNSW, Aurora, MemoryDB) |
| Task 2.1: Choose a data store | Skill 2.1.4 | Integrate migration tools (AWS Transfer Family) |
| Task 2.1: Choose a data store | Skill 2.1.5 | Implement data migration/remote access (Redshift federated queries, Spectrum) |
| Task 2.1: Choose a data store | Skill 2.1.6 | Manage locks to prevent access (Redshift, RDS) |
| Task 2.1: Choose a data store | Skill 2.1.7 | Manage open table formats (Apache Iceberg) |
| Task 2.1: Choose a data store | Skill 2.1.8 | Describe vector index types (HNSW, IVF) |
| Task 2.2: Understand data cataloging | Skill 2.2.1 | Use data catalogs to consume data |
| Task 2.2: Understand data cataloging | Skill 2.2.2 | Build and reference a technical data catalog (Glue Data Catalog, Hive) |
| Task 2.2: Understand data cataloging | Skill 2.2.3 | Discover schemas and use Glue crawlers |
| Task 2.2: Understand data cataloging | Skill 2.2.4 | Synchronize partitions with a data catalog |
| Task 2.2: Understand data cataloging | Skill 2.2.5 | Create new source/target connections for cataloging |
| Task 2.2: Understand data cataloging | Skill 2.2.6 | Create and manage business data catalogs (SageMaker Catalog) |
| Task 2.3: Manage lifecycle of data | Skill 2.3.1 | Perform load/unload operations (S3 ↔ Redshift) |
| Task 2.3: Manage lifecycle of data | Skill 2.3.2 | Manage S3 Lifecycle policies for storage tier changes |
| Task 2.3: Manage lifecycle of data | Skill 2.3.3 | Expire data by age using S3 Lifecycle |
| Task 2.3: Manage lifecycle of data | Skill 2.3.4 | Manage S3 versioning and DynamoDB TTL |
| Task 2.3: Manage lifecycle of data | Skill 2.3.5 | Delete data to meet business and legal requirements |
| Task 2.3: Manage lifecycle of data | Skill 2.3.6 | Protect data with resiliency and availability |
| Task 2.4: Design data models | Skill 2.4.1 | Design schemas for Redshift, DynamoDB, and Lake Formation |
| Task 2.4: Design data models | Skill 2.4.2 | Address changes to characteristics of data |
| Task 2.4: Design data models | Skill 2.4.3 | Perform schema conversion (SCT, DMS) |
| Task 2.4: Design data models | Skill 2.4.4 | Establish data lineage (SageMaker ML Lineage Tracking) |
| Task 2.4: Design data models | Skill 2.4.5 | Best practices for indexing, partitioning, compression |
| Task 2.4: Design data models | Skill 2.4.6 | Describe vectorization concepts (Bedrock knowledge base) |

### Domain 3: Data Operations and Support (22%)

| Task | Skill | Deskripsi |
|------|-------|-----------|
| Task 3.1: Automate data processing | Skill 3.1.1 | Orchestrate data pipelines (MWAA, Step Functions) |
| Task 3.1: Automate data processing | Skill 3.1.2 | Troubleshoot Amazon managed workflows |
| Task 3.1: Automate data processing | Skill 3.1.3 | Call SDKs to access Amazon features from code |
| Task 3.1: Automate data processing | Skill 3.1.4 | Use features of AWS services to process data (EMR, Redshift, Glue) |
| Task 3.1: Automate data processing | Skill 3.1.5 | Consume and maintain data APIs |
| Task 3.1: Automate data processing | Skill 3.1.6 | Prepare data for transformation (DataBrew, SageMaker) |
| Task 3.1: Automate data processing | Skill 3.1.7 | Query data (Athena) |
| Task 3.1: Automate data processing | Skill 3.1.8 | Use Lambda to automate data processing |
| Task 3.1: Automate data processing | Skill 3.1.9 | Manage events and schedulers (EventBridge) |
| Task 3.2: Analyze data | Skill 3.2.1 | Visualize data (DataBrew, QuickSight) |
| Task 3.2: Analyze data | Skill 3.2.2 | Verify and clean data (Lambda, Athena, Jupyter, Data Wrangler) |
| Task 3.2: Analyze data | Skill 3.2.3 | Use SQL in Redshift and Athena to query/create views |
| Task 3.2: Analyze data | Skill 3.2.4 | Use Athena notebooks with Apache Spark |
| Task 3.2: Analyze data | Skill 3.2.5 | Describe tradeoffs between provisioned and serverless |
| Task 3.2: Analyze data | Skill 3.2.6 | Define aggregation, rolling average, grouping, pivoting |
| Task 3.3: Maintain and monitor | Skill 3.3.1 | Extract logs for audits |
| Task 3.3: Maintain and monitor | Skill 3.3.2 | Deploy logging and monitoring solutions |
| Task 3.3: Maintain and monitor | Skill 3.3.3 | Use notifications during monitoring to send alerts |
| Task 3.3: Maintain and monitor | Skill 3.3.4 | Troubleshoot performance issues |
| Task 3.3: Maintain and monitor | Skill 3.3.5 | Use CloudTrail to track API calls |
| Task 3.3: Maintain and monitor | Skill 3.3.6 | Troubleshoot and maintain pipelines (Glue, EMR) |
| Task 3.3: Maintain and monitor | Skill 3.3.7 | Use CloudWatch Logs for application data |
| Task 3.3: Maintain and monitor | Skill 3.3.8 | Analyze logs (Athena, EMR, OpenSearch, CloudWatch Logs Insights) |
| Task 3.4: Ensure data quality | Skill 3.4.1 | Run data quality checks during processing |
| Task 3.4: Ensure data quality | Skill 3.4.2 | Define data quality rules (DataBrew) |
| Task 3.4: Ensure data quality | Skill 3.4.3 | Investigate data consistency |
| Task 3.4: Ensure data quality | Skill 3.4.4 | Describe data sampling techniques |
| Task 3.4: Ensure data quality | Skill 3.4.5 | Implement data skew mechanisms |

### Domain 4: Data Security and Governance (18%)

| Task | Skill | Deskripsi |
|------|-------|-----------|
| Task 4.1: Apply authentication | Skill 4.1.1 | Update VPC security groups |
| Task 4.1: Apply authentication | Skill 4.1.2 | Create and update IAM groups, roles, endpoints |
| Task 4.1: Apply authentication | Skill 4.1.3 | Create and rotate credentials (Secrets Manager) |
| Task 4.1: Apply authentication | Skill 4.1.4 | Set up IAM roles for access (Lambda, API Gateway, CLI) |
| Task 4.1: Apply authentication | Skill 4.1.5 | Apply IAM policies (S3 Access Points, PrivateLink) |
| Task 4.1: Apply authentication | Skill 4.1.6 | Describe managed vs unmanaged services |
| Task 4.1: Apply authentication | Skill 4.1.7 | Use domain/projects for SageMaker Unified Studio |
| Task 4.2: Apply authorization | Skill 4.2.1 | Create custom IAM policies |
| Task 4.2: Apply authorization | Skill 4.2.2 | Store credentials (Secrets Manager, Parameter Store) |
| Task 4.2: Apply authorization | Skill 4.2.3 | Provide database users/groups/roles access (Redshift) |
| Task 4.2: Apply authorization | Skill 4.2.4 | Manage permissions through Lake Formation |
| Task 4.2: Apply authorization | Skill 4.2.5 | Apply authorization methods (RBAC, TBAC, ABAC) |
| Task 4.2: Apply authorization | Skill 4.2.6 | Construct policies for least privilege |
| Task 4.3: Encryption and masking | Skill 4.3.1 | Apply data masking and anonymization |
| Task 4.3: Encryption and masking | Skill 4.3.2 | Use encryption keys (KMS) |
| Task 4.3: Encryption and masking | Skill 4.3.3 | Configure encryption across account boundaries |
| Task 4.3: Encryption and masking | Skill 4.3.4 | Enable encryption in transit |
| Task 4.4: Prepare logs for audit | Skill 4.4.1 | Use CloudTrail to track API calls |
| Task 4.4: Prepare logs for audit | Skill 4.4.2 | Use CloudWatch Logs to store application logs |
| Task 4.4: Prepare logs for audit | Skill 4.4.3 | Use CloudTrail Lake for centralized logging queries |
| Task 4.4: Prepare logs for audit | Skill 4.4.4 | Analyze logs (Athena, CloudWatch Logs Insights, OpenSearch) |
| Task 4.4: Prepare logs for audit | Skill 4.4.5 | Integrate AWS services for logging (EMR) |
| Task 4.5: Data privacy and governance | Skill 4.5.1 | Grant permissions for data sharing (Redshift) |
| Task 4.5: Data privacy and governance | Skill 4.5.2 | Implement PII identification (Macie, Lake Formation) |
| Task 4.5: Data privacy and governance | Skill 4.5.3 | Prevent backups/replications to disallowed Regions |
| Task 4.5: Data privacy and governance | Skill 4.5.4 | View configuration changes (AWS Config) |
| Task 4.5: Data privacy and governance | Skill 4.5.5 | Maintain data sovereignty |
| Task 4.5: Data privacy and governance | Skill 4.5.6 | Manage data access through SageMaker Catalog projects |
| Task 4.5: Data privacy and governance | Skill 4.5.7 | Describe governance framework and data sharing patterns |

---

## 🚀 Cara Menggunakan

1. Buka [https://lintanggilang.github.io/wuidi-de-soal/](https://lintanggilang.github.io/wuidi-de-soal/)
2. Pilih **Domain** → **Task** → **Skill** untuk belajar per topik
3. Atau klik **Simulasi Ujian** untuk latihan 120 soal sekaligus dengan skor realtime
4. Klik pilihan jawaban untuk melihat apakah benar/salah
5. Penjelasan otomatis muncul setelah menjawab

---

## 🛠️ Teknologi

- HTML, CSS, JavaScript vanilla (tanpa framework)
- Tanpa backend / database
- Static hosting via GitHub Pages
- Dark mode support
- Responsive design

---

## 👤 Author

**Created by Lintang Gilang and Kiro Agent at 04 June 2026**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lintang%20Gilang-blue?logo=linkedin)](https://www.linkedin.com/in/lintanggilang/)

---

## 📄 License

Project ini dibuat untuk tujuan edukasi dan persiapan sertifikasi AWS Data Engineer Associate.
