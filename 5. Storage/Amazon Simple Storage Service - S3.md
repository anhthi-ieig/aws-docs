## Amazon Simple Storage Service - S3

## S3 Storage Classes

1. S3 Standard

- S3 Standard offers high durability, availability, and performance `object storage for frequently accessed data`

- S3 Standard `delivers low latency and high throughput`, S3 Standard is appropriate for a wide variety of use cases, including

  - Cloud applications
  - Dynamic websites
  - Content distribution
  - Mobile and gaming applications
  - Big data analytics

- First byte latency: milliseconds

2. S3 Standard Infrequent Access - Standard IA

3. S3 One-Zone Infrequent Access - S3 One-Zone IA

- S3 One Zone-IA is for data that is `accessed infrequently but requires rapid access when needed`
- S3 One Zone-IA `stores data in a single Availability Zone` and `costs 20% less than S3 Standard-IA` while `other S3 Storage Classes store data in at lest 3 Availability Zone`

4. S3 Intelligent Tiering

- The S3 Intelligent-Tiering storage class is `designed to optimize costs by automatically moving data` to the most cost-effective access tier, `without performance impact or operational overhead`

- It `works by storing objects in two access tiers`

  - One tier that is optimized for frequent access
  - Another lower-cost tier that is optimized for infrequent access

- Data at in S3 Glacier is `automatically server-side encrypted` using AES-256

- First byte latency: milliseconds

5. S3 Glacier

- Amazon S3 Glacier is a `secure, durable, and low-cost storage class` for `data archiving and long-term backup`

- First byte latency: a flew hours

6. S3 Glacier Deep Archive

- S3 Glacier Deep Archive is the `secure, durable, and lowest-cost storage class` and `supports long-term retention and digital preservation` for data that

  - May be accessed once or twice in a year
  - Retain data sets for 7-10 years or longer
  - For backup and disaster recovery

- First byte latency: 12 to 48 hours

- Usually used for
  - Financial Services
  - Healthcare
  - Public Sectors
