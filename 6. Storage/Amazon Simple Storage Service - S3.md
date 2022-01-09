## Amazon Simple Storage Service (S3) - Scalable storage in the cloud

- Amazon S3 is `object storage service` built to `store and retrieve any type and amount of data` from anywhere

- Amazon S3 allow to `enable versioning to create multiple versions of your files` in order to protect against accidental deletion and to use a previous version

- Amazon S3 `is a regional service`, but `bucket names must be globally unique`

- Amazon S3 allow to `store files up to 5TB`. If the file is more than 5TB, must use "multi-part upload"

- Amazon S3 allow to `set security at the bucket level or individual object level`

  - Access control lists (ACLs)
  - Bucket policies
  - Access point policies

- Amazon S3 can be used for

  - Static website
  - Data lakes and big data analytics
  - Backup and restore
  - Disaster recovery
  - Application and Media hosting
  - ...

- `Amazon S3 Lifecycle allows you to automatically transfer data to a different storage classes` without any changes to your application `for cost saving`

## Amazon S3 Storage Classes

1. S3 Standard

- `Durability of 99.999999999%` of objects `across multiple AZs`
- `Low latency and high throughput performance`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - General-purpose storage
  - Frequently accessed data

2. S3 Intelligent Tiering

- `Reduces your storage costs` by `automatically moving data to the most cost-effective access tier` based on access frequency
- `Low latency and high throughput performance`
- Recommend for

  - `Data with unknown or changing access pattern`

3. S3 Standard Infrequent Access - Standard IA

- For `data that is accessed less frequently`, `but requires rapid access when needed`
- `Durability of 99.999999999%` of objects `across multiple AZs`
- Same low latency and high throughput performance of S3 Standard `but cheaper`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - `Long-lived data`
  - `Infrequently accessed`
  - `Millisecond access when needed`

4. S3 One-Zone Infrequent Access - S3 One-Zone IA

- For `data that is accessed less frequently`, `but requires rapid access when needed`
- `Durability of 99.999999999%` of objects `across multiple AZs`
- `Data is stored in a single AZ` and `costs 20% less than S3 Standard-IA`
- `Data stored in this storage class can be lost`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - `Re-creatable data`
  - `Infrequently accessed with millisecond access`
  - `Availability and durability not essential`

5. Amazon S3 Glacier Flexible Retrieval (Formerly S3 Glacier)

- `Long-term data storage and archival for lower costs`
- `Data retrieval takes longer`
- 3 retrieval options: 1-5 minutes, 3-5 hours, or 5-12 hours
- Data stored across multiple Availability Zones
- Recommend for

  - `Long-term backups`
  - Cheaper storage options

6. S3 Glacier Deep Archive

- Is the `Lowest-cost storage class`
- Designed for `durability of 99.999999999%`
- `Retrieval time within 12 hours`
- Data stored across multiple Availability Zones
- Recommend for

  - Data that may be `accessed once or twice in a year`
  - Data that will be `retained for 7-10 years`

7. S3 Outposts

- `Provides object storage on-premises`
- A single storage class
- `Store data across multiple devices and servers`
- Recommend for

  - `Data that needs to be kept local`
  - Demanding application performance needs

## Amazon S3 Security

1. User based

- Using IAM Policies: which API calls should be allowed for a specific IAM user

2. Resource based

- Using Bucket Policies
- Using Object/Bucket Access Control List - ACL

## Amazon S3 Replication

- Must enable bucket versioning in source and destination
- Support Same Region Replication(SRR) and Cross Region Replication(CRR)
- Buckets can be in different AWS accounts
- Replication is asynchronous

## Amazon S3 Transfer Acceleration

- Amazon S3 Transfer Acceleration `leverages AWS Edge Locations` to `enables fast, easy, and secure transfers of files` over long distances `between your client and your Amazon S3 buckets`

## S3 Object Lock

- S3 Object Lock allow you to `store objects using a write-once-read-many (WORM) model`

- S3 Object Lock can help `prevent objects from being deleted or overwritten for a fixed amount of time or indefinitely`

## S3 Glacier Vault Lock

- S3 Glacier Vault Lock allows you to easily `deploy and enforce compliance controls for individual S3 Glacier vaults` with `a vault lock policy`

- You can specify controls such as “write once read many” (WORM) in a vault lock policy and lock the policy from future edits. `Once locked, the policy can no longer be changed`

## Amazon S3 Access Logs

- All access and changes from any accounts are made in Amazon S3 buckets can be logged to another S3 bucket
