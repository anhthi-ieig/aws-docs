## Amazon Simple Storage Service (S3) - Scalable storage in the cloud

- Amazon S3 is `object storage service` built to `store and retrieve any type and amount of data` from anywhere

- You can `set security at the bucket level or individual object level` using `access control lists (ACLs), bucket policies, or access point policies`

- You can `enable versioning to create multiple versions of your file` in order to protect against accidental deletion and to use a previous version

- `S3 Lifecycle allows your data will automatically transfer to a different storage class` without any changes to your application for cost saving

- You can `use S3 access logs to track the access to your buckets and objects`

- S3 is `a regional service, but bucket names must be globally unique`

## S3 Storage Classes

1. S3 Standard

- `General-purpose storage`
- Data stored across multiple AZs
- `Low latency and hight throughput`
- Recommend for

  - `Frequently accessed data`

2. S3 Intelligent Tiering

- `Automatically moves your data to the most cost-effective storage class`
- `Automatic cost savings`
- No retrieval fees
- Data stored across multiple Availability Zones
- Recommend for

  - `Data with unknown or changing access pattern`

3. S3 Standard Infrequent Access - Standard IA

- `Data accessed less frequently but requires rapid access`
- Data stored across multiple Availability Zones
- Cheaper than S3 Standard
- Recommend for

  - `Long-lived data`
  - `Infrequently accessed`
  - `Millisecond access when needed`

4. S3 One-Zone Infrequent Access - S3 One-Zone IA

- Like S3 Standard-IA but `data stored in a single Availability Zone`
- Costs 20% less than S3 Standard-IA
- `Data stored in this storage class can be lost`
- Recommend for

  - `Re-creatable data`
  - `Infrequently accessed with millisecond access`
  - `Availability and durability not essential`

5. S3 Glacier

- `Long-term data storage and archival for lower costs`
- `Data retrieval takes longer`
- 3 retrieval options: 1-5 minutes, 3-5 hours, or 5-12 hours
- Data stored across multiple Availability Zones
- Recommend for

  - `Long-term backups`
  - Cheaper storage options

6. S3 Glacier Deep Archive

- `Like S3 Glacier but longer access times`
- 2 retrieval options: 12 hours or 48 hours
- `Cheapest of all S3 options`
- Data stored across multiple Availability Zones
- Recommend for

  - `Long-term data archival accessed once or twice a year`
  - Retaining data for regulatory compliance requirements

7. S3 Outposts

- `Provides object storage on-premises`
- A single storage class
- `Store data across multiple devices and servers`
- Recommend for

  - `Data that needs to be kept local`
  - Demanding application performance needs
