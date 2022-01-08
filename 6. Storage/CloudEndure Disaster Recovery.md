## CloudEndure Disaster Recovery (AWS DRS) - Highly automated disaster recovery

- AWS Elastic Disaster Recovery `minimizes downtime and data loss` with fast, reliable recovery of on-premises and cloud-based applications `using affordable storage, minimal compute, and point-in-time recovery`

- AWS Elastic Disaster Recovery `continuously replicates your machines` into a low-cost staging area in your target AWS account and preferred Region

## Disaster Recovery Options

- There are multiple options for recovery that trade cost and time to recover

1. Backup and Restore

- You backup your data and restore it to a new infrastructure
- Take hours to complete

2. Pilot Light

- Data is replicated to another Region with the minimal services running
- Take 10 minutes to complete

3. Warm Standby

- Scaled down copy of your infrastructure running ready to scale up
- Take few minutes to complete

4. Multi-site active/active

- Scaled up copy of your infrastructure in another region
- It's real-time
