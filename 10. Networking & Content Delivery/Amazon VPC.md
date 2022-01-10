## Amazon VPC - Isolated cloud resources

- Amazon VPC is `a foundation service` that allow you to `create a secure private network on the AWS cloud` where `you can launch your resource`

- Amazon VPC `spans AZs in a Region`

- You have complete control over your virtual networking environment, including

  - Selection of your own IP address ranges
  - Creation of subnets
  - Configuration of Route Tables and Network Gateways

## Subnets

- Subnets allow you to `partition your network inside your VPC`

- A subnet is associate with an AZ

- There are 2 types of subnets

  - Public subnets: is accessible from the internet
  - Private subnets:

## Route Table

- A route table `contains a set of rules, called routes,` that are `used to determine where network traffic from your subnet or gateway is directed`

## Internet Gateway

- Internet Gateway `allow your VPC connect to the internet`

## NAT Gateways(AWS managed) / NAT Instances(self-managed)

- NAT Gateways/NAT Instances allow `your instance in your private subnets to access to the internet` while `remaining private`

## Network Access Control List (NACL)

- NACL is `an optional layer of security for your VPC` that `acts as a firewall` for `controlling traffic in and out of one or more subnets`

- NACL can `have Allow or Deny rules` and are `attached at the Subnet level`

## Security Group

- Security Group acts as a firewall to control traffic in an out for EC2 instances

- Security Group can `only have Allow rule`

## VPC Flow Logs

- VPC Flow Logs allows to capture information about IP traffic going to your interfaces

- VPC Flow Logs helps to monitor and troubleshoot connectivity issues

## VPC Peering

- VPC Peering allows to connect 2 VPCs, privately using AWS network

- You can create a VPC peering connection between

  - Your own VPCs
  - VPCs in different regions (also known as an inter-region VPC peering connection)
  - VPCs in two different AWS accounts

## VPC Endpoint

- VPC Endpoint allow you to `connect to AWS services using a private network` instead a public network. It gives you `enhanced security and low latency to access AWS services`
