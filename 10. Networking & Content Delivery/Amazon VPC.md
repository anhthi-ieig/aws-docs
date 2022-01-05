## Amazon VPC - Isolated cloud resources

- Amazon VPC is `a foundation service` that allow you to `create a secure private network on the AWS cloud` where `you can launch your resource`

- Amazon VPC `spans AZs in a Region`

- You have complete control over your virtual networking environment, including

  - Selection of your own IP address ranges
  - Creation of subnets
  - Configuration of Route Tables and Network Gateways

## Network Access Control List (NACL)

- A Network Access Control List is `an optional layer of security for your VPC` that `acts as a firewall` for `controlling traffic in and out of one or more subnets`

- You might set up network ACLs with rules similar to your security groups in order to add an additional layer of security to your VPC

## Route Table

## Internet Gateway

## VPC Endpoint

## VPC Peering

- A VPC peering connection is `a networking connection between two VPCs` that enables you to `route traffic between them privately`

- Instances in either VPC `can communicate with each other` as if they are within the same network

- You can create a VPC peering connection between

  - Your own VPCs
  - VPCs in different regions (also known as an inter-region VPC peering connection)
  - VPCs in two different AWS accounts
