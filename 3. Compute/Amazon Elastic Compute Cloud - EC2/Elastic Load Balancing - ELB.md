## Elastic Loading Balancing (ELB) - Distribute incoming traffic across multiple targets

- Elastic Load Balancing allow you to `automatically distributes incoming application traffic` across multiple targets(Ex: EC2 instances) `in one or more Availability Zones`

- Elastic Load Balancing `exposes a single point of access(DNS)` to your applications

- Elastic Load Balancing `does health checks to your EC2 instances`

- Elastic Load Balancing offers three types of load balancers

  - Application Load Balancer: for HTTP/HTTPS traffic - Layer 7
  - Network Load Balancer: for TCP traffic, ultra high-performance - Layer 4
  - Classic Load Balancer: slowly retiring - Layer 4 & 7
