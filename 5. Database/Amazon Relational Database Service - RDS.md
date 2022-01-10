## Amazon Relational Database Service (RDS)

- Amazon RDS is `a managed service` that makes it `easy to set up, operate, and scale a relational database` in the cloud

- Amazon RDS `provides cost-efficient and resizable capacity` while `automating time-consuming administration tasks` such as `hardware provisioning, database setup, patching and backups`

- Amazon RDS can `automatically back up your database` and `keep your database software up to date` with the latest version

- Amazon RDS supports

  - MySQL
  - MariaDB
  - Oracle
  - SQL Server
  - PostgreSQL

## RDS Deployment

1. Read Replicas

- Main purpose is `scalability`

- Provide `enhanced performance and durability` for RDS database instances `by create one or more replicas of a primary DB instance` and `serve high-volume read traffic from multiple copies of primary DB instance`

- The data is only written to the primary DB instance

2. Multi-AZ

- Main purpose is `high availability`

- With Multi-AZ deployment, Amazon RDS `automatically creates a primary DB instance` and `synchronously replicates the data to standby DB instances in different AZs`. If the main DB instance crashes, the standby DB instances will be used

3. Multi-Region

- Main purpose is `disaster recovery and local performance`
