## Security Group

- Security Group `acts as a firewall to control traffic in an out for EC2 instances`

- Security Group can `only have Allow rule` and `act at the instance level`, not the subnet level

- You can assign up to five security groups to the EC2 instance

- Security Groups start with `only an outbound rule by default` that allows all traffic to leave the instances. You must add rules to enable any inbound traffic or to restrict the outbound traffic
