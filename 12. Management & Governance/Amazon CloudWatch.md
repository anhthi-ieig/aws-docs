## Amazon CloudWatch - Monitor resources and applications

- Amazon CloudWatch is `a monitoring service for AWS cloud resources and the applications` you run on AWS

- You can use Amazon CloudWatch to
  - `Collect and track metrics`
  - `Collect and monitor log files`
  - `Set alarms`

## Amazon CloudWatch Metrics

- Metrics are data about the performance of your systems, such as

  - EC2 instances: CPU utilization, status check, network
  - EBS volume: Read/Write
  - S3 buckets: BucketSizeBytes, NumberOfObject, AllRequests
  - Billing: Total Estimated Charge
  - Your own metrics

## Amazon CloudWatch Alarms

- CloudWatch Alarms are used to trigger actions for any metric, such as

  - Amazon EC2 instance CPU utilization
  - Amazon ELB request latency
  - Amazon DynamoDB table throughput
  - Amazon SQS queue length
  - Charges on your AWS bill

## Amazon CloudWatch Logs

- CloudWatch Logs `enables you to monitor, store, access your log files` `from all of your on-premises systems, and AWS services` that you use

## Amazon CloudWatch Events/Event Bridge

- CloudWatch Events allow to `schedule automated actions that self-trigger at certain times` using cron or rate expressions
