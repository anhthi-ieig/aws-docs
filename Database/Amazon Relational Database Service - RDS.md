## Amazon Relational Database Service - RDS

- Amazon RDS is `a managed service` that makes it `easy to set up, operate, and scale a relational database` in the cloud

- Amazon RDS `provides cost-efficient and resizable capacity` while `automating time-consuming administration tasks` such as hardware provisioning, database setup, patching and backups

- Amazon RDS supports

  - MySQL
  - MariaDB
  - Oracle
  - SQL Server
  - PostgreSQL

## Multi-AZ deployments

- Main purpose is `high availability`

- With Multi-AZ DB Instance, Amazon RDS `automatically creates a primary DB Instance` and `synchronously replicates the data to standby instances in different AZs`

## Multi-Region deployments

- Main purpose is `disaster recovery and local performance`

## Read Replicas

- Main purpose is `scalability`

- Read Replicas provide `enhanced performance and durability` for RDS database instances `by create one or more replicas of a primary DB Instance` and `serve high-volume read traffic from multiple copies of your primary DB Instance`
