## AWS responsibility "Security of the Cloud"

- AWS is responsible for `protecting the infrastructure that runs all of the services` offered in the AWS Cloud, includes

  - Hardware/Global infrastructure: Regions, Availability Zones, Edge Locations
  - Software: Compute, Storage, Database, Networking
  - Managed AWS Services: S3, RDS, DynamoDB...

## Customer responsibility "Security in the Cloud"

- Customers are responsible for managing their data, classifying their assets, and using IAM tools to apply the appropriate permissions, includes

  - Operating System
  - Platforms
  - Applications
  - Network and Firewall configuration
  - Identity and Access Management
  - Customer data
  - Client-side Data Encryption and Data Integrity Authentication
  - Server-side Encryption(File System and/or Data)
  - Networking Traffic Protection(Encryption, Integrity, Identity)

## Shared Control

- Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives, includes

  - Patch Management: `AWS is responsible for patching and fixing flaws within the infrastructure`, but `customers are responsible for patching their guest OS and applications`

  - Configuration Management: `AWS maintains the configuration of its infrastructure devices`, but `customers are responsible for configuring their own guest operating systems, databases, and applications`

  - Awareness & Training: `AWS trains AWS employees`, but `customers must train their own employees`
