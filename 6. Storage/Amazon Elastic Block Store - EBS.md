## Amazon Elastic Block Store (EBS) - EC2 block storage volumes

- Amazon EBS is `a block-level storage service` for `use with Amazon EC2`. Amazon EBS can deliver performance for workloads that `require the lowest-latency access` to data from `a single EC2 instance`

- `One or multiple Amazon EBS` can be `attached or detached to an EC2 instance`

- Amazon EBS `is locked to a specific AZ`

- Recommend for

  - Running a database on an instance
  - Quickly accessible data
  - Long-term data storage

## Amazon EBS Snapshots

- Amazon EBS Snapshot is `a backup of your EBS volume at a point of time`
- Amazon EBS Snapshot is `able to copied across AZs or Region`
