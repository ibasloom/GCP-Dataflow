# GCP-Dataflow Job Creation Steps

Interacting with three GCP services is necessary to create a dataflow job in GCP.

### 1. [Buckets / Cloud Storage](https://console.cloud.google.com/storage/)

Buckets are logical containers for files in cloud storage services like S3, Google Cloud, and Azure Blob Storage. They are scalable and provide high durability and availability for various purposes, including hosting static websites and storing backups. Access can be controlled using policies, encryption, and authentication mechanisms to ensure data security and privacy.

### 2. [VPC networks](https://console.cloud.google.com/networking/networks/)

Google Cloud Platform (GCP) Virtual Private Cloud (VPC) provides a logically isolated virtual network environment in GCP. It offers complete control over networking, including IP range selection, subnet creation, and route table configuration. VPC offers advanced features like firewall rules, VPN connectivity, and cloud router for dynamic routing. It allows for the creation of private clusters and can be connected to on-premises networks.

### 3. [Dataflow](https://console.cloud.google.com/dataflow/)

Google Cloud Dataflow is a fully-managed, serverless data processing service on the Google Cloud Platform. It enables the development of data pipelines and transformation workflows at any scale, utilizing Apache Beam's programming model. Dataflow provides auto-scaling, monitoring, and cost optimization for streaming and batch data processing with integration to other GCP services.

### [Network Link](https://cloud.google.com/dataflow/docs/guides/specifying-networks)
