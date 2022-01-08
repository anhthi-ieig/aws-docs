## Amazon Elastic File System (EFS) - Fully managed file system for EC2

- Amazon EFS is `a serverless, elastic file system` for use with `Amazon compute and on-premises servers`

- Amazon EFS can `automatically scale from gigabytes to petabytes of data` `without needing to provision storage`

- Amazon EFS `only support the Linux file system` in `multi AZs`

- `Thousands of compute instances can access an Amazon EFS file system at the same time`, and Amazon EFS `provides consistent performance to each compute instance`

- Amazon EFS can used for

  - Amazon EC2
  - Amazon ECS
  - Amazon EKS
  - AWS Fargate
  - AWS Lambda functions

## Amazon EFS Storage Classes

1. Amazon EFS Standard

- Store data with and `across multiple AZs`

2. Amazon EFS Standard-Infrequent Access (EFS Standard-IA)

- Store data with and `across multiple AZs`

- Lifecycle Management `automatically moves your data from the EFS Standard to the EFS Standard-IA storage class` according to the lifecycle policy you choose

3. Amazon EFS One Zone

- Store data redundantly `within a single AZ`, at `a 47% lower price compared to Standard`

4. Amazon EFS One Zone-Infrequent Access (EFS One Zone-IA)

- Store data redundantly `within a single AZ`, at `a 47% lower price compared to Standard`

- Lifecycle Management `automatically moves your data from the EFS One Zone to the EFS One Zone-IA storage class` according to the lifecycle policy you choose
