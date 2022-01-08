## Amazon Route 53 - 53 Scalable domain name system (DNS)

- Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service

- It `is designed to route end users to Internet applications` by translating domain names(Ex: www.example.com) into the numeric IP addresses(Ex: 192.0.2.1) that computers use to connect to each other

- Amazon Route 53 allows to

  - `Domain name registration`
  - `Perform health checks on AWS resources`
  - `Support hybrid cloud architectures`

## Routing Policies

1. Simple routing policy

- `Use for a single resource` that performs a given function for your domain

2. Failover routing policy

- Use when you want to `configure active-passive failover`

3. Geolocation routing policy

- Use when you want to `route traffic based on the location of your users`

4. Geoproximity routing policy

- Use when you want to `route traffic based on the location of your resources` and, optionally, `shift traffic from resources in one location to resources in another`

5. Latency routing policy

- Use when you have `resources in multiple AWS Regions` and you want to `route traffic to the Region that provides the best latency with less round-trip time`

6. Multivalue answer routing policy

- Use when you want Route 53 to respond to DNS queries with up to eight healthy records selected at random

7. Weighted routing policy

- Use to route traffic to multiple resources in proportions that you specify
