## Amazon Elastic Compute Cloud (EC2) - Virtual servers in the cloud

- Amazon EC2 is `a web service` that provides `resizable compute capacity in the cloud`. It is designed to make web-scale computing easier for developers

## Elastic Loading Balancing

- Automatically distributes your incoming application traffic across multiple EC2 instances

## Auto Scaling

- Automatically add or remove EC2 instances across AZs, based on need and changing demand

## Amazon EC2 Pricing

1. On-Demand Instances

- An On-Demand Instance is an instance that you `use on-demand with fixed prices and cannot be interrupted`

- You `have full control over its lifecycle` — you decide when to launch, stop, hibernate, start, reboot, or terminate it

- There is `no upfront payment` and `no long-term commitment required`

- You `pay only for the seconds that your On-Demand Instances are running`

2. Reserved Instances

- Reserved Instances provide you with `significant savings (up to 75%) costs compared to On-Demand prices`. You can pay All Upfront(max discount), Partial Upfront or No Upfront

- You can purchase a Reserved Instance `for a one-year or three-year commitment`

- `Reserved instances cannot be interrupted`

3. Scheduled Instance

- With Scheduled Reserved Instances, you can `reserve capacity that is scheduled to recur daily, weekly, or monthly, with a specified start time and duration, for a one-year term`

- After you complete your purchase, the instances are `available to launch during the time windows that you specified`

4. Spot Instance

- Spot Instances let you `take advantage of unused EC2 capacity` in the AWS cloud

- Spot Instances are available at `up to a 90% discount compared to On-Demand prices`

- These `can be terminated at short notice`, so these are `not suitable for critical workloads`

4. Dedicated Hosts

- Dedicated Host `is a physical server` fully dedicated for running your instances

- Dedicated Hosts can help you `reduce costs by allowing you to use your existing server-bound software licenses`

- `Can be purchased as a Reservation for up to 70% discount compared to On-Demand prices`

5. Dedicated Instances

- Dedicated Instances run in a VPC on hardware that's dedicated to a single customer

- Dedicated Instances that `belong to different AWS accounts are physically isolated at a hardware level`. However, Dedicated Instances might `share hardware with other instances from the same AWS account that are not Dedicated Instances`

6. Saving Plans

- Savings Plans are a flexible pricing model that offer low prices, `in exchange for a commitment to a consistent amount of usage` (measured in $/hour) for a 1 or 3 year term

- Savings Plans allow the `flexibility to change compute services, instance types, operating systems or Region`

- The EC2 Instance Savings Plans offer up to `72% savings compared to On-Demand`

- Savings Plans can be shared across various compute services like EC2, Fargate, and Lamda

## Note

- `1 minute minimum charge` for EC2 instances
