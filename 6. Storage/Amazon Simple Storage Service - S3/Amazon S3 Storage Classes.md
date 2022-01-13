## S3 Standard

- `Durability of 99.999999999%` of objects `across multiple AZs`
- `Low latency and high throughput performance`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - General-purpose storage
  - Frequently accessed data

## S3 Intelligent Tiering

- `Reduces your storage costs` by `automatically moving data to the most cost-effective access tier` based on access frequency
- `Low latency and high throughput performance`
- Recommend for

  - `Data with unknown or changing access pattern`

## S3 Standard Infrequent Access - Standard IA

- For `data that is accessed less frequently`, `but requires rapid access when needed`
- `Durability of 99.999999999%` of objects `across multiple AZs`
- Same low latency and high throughput performance of S3 Standard `but cheaper`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - `Long-lived data`
  - `Infrequently accessed`
  - `Millisecond access when needed`

## S3 One-Zone Infrequent Access - S3 One-Zone IA

- For `data that is accessed less frequently`, `but requires rapid access when needed`
- `Durability of 99.999999999%` of objects `across multiple AZs`
- `Data is stored in a single AZ` and `costs 20% less than S3 Standard-IA`
- `Data stored in this storage class can be lost`
- `Supports SSL for data in transit` and `encryption of data at rest`
- Recommend for

  - `Re-creatable data`
  - `Infrequently accessed with millisecond access`
  - `Availability and durability not essential`

## Amazon S3 Glacier Flexible Retrieval (Formerly S3 Glacier)

- `Long-term data storage and archival for lower costs`
- `Data retrieval takes longer`
- 3 retrieval options: 1-5 minutes, 3-5 hours, or 5-12 hours
- Data stored across multiple Availability Zones
- Recommend for

  - `Long-term backups`
  - Cheaper storage options

## S3 Glacier Deep Archive

- Is the `Lowest-cost storage class`
- Designed for `durability of 99.999999999%`
- `Retrieval time within 12 hours`
- Data stored across multiple Availability Zones
- Recommend for

  - Data that may be `accessed once or twice in a year`
  - Data that will be `retained for 7-10 years`

## S3 Outposts

- `Provides object storage on-premises`
- A single storage class
- `Store data across multiple devices and servers`
- Recommend for

  - `Data that needs to be kept local`
  - Demanding application performance needs
