# AWS S3
Amazon S3 (Simple Storage Service) is a massively scalable cloud object storage service used by developers and enterprises to store files, application assets, and massive data lakes. It lets you securely store, retrieve, and archive any amount of data ranging from a few megabytes to hundreds of exabytes

---

## How it WorksBuckets: 

- Data is stored in logical containers called buckets. Bucket names must be globally unique across all AWS accounts worldwide.
- Objects: Every file is stored as an "object" (the data itself alongside its metadata and a unique key name). Objects can range in size from 0 bytes up to 50 TB.
- Metadata & Annotations: S3 supports user-defined metadata and features like AWS S3 Annotations, which allow you to attach rich, searchable, mutable context to objects at scale.

## Key FeaturesVirtually Unlimited Scaling: 

- You do not need to provision storage space in advance; the system scales automatically to accommodate growing datasets.
- High Durability & Availability: S3 is engineered for 99.999999999% data durability by automatically replicating objects across multiple physical Availability Zones.
- Cost-Effective Tiers: It offers multiple storage classes designed for different access patterns, ranging from S3 Standard (frequent access) to S3 Glacier (low-cost long-term archiving). You can set up lifecycle policies to automatically transition files between tiers to save money.
- Integrations & AI Ready: S3 is the foundational storage layer for petabyte-scale analytics and AI workloads, featuring specialized tools like S3 Tables (for Apache Iceberg data lakes) and S3 Vectors (for AI vector embeddings).

## Common Use CasesData Lakes: 

- Running analytics and building data lakehouse architectures using AWS or third-party engines.Application Backups & Disaster Recovery: Storing reliable, decentralized copies of databases and critical files.
- Software Distribution: Securely serving software packages and digital assets using signed URLs.
- AI/ML Dataset Storage: Hosting high-resolution video, seismic datasets, and massive training models.

---
