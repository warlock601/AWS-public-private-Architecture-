# AWS-public-private-Architecture-

This example demonstrates how to create a VPC that you can use for servers in a production environment. To improve resiliency, you deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. For additional security, you deploy the servers in private subnets. The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, you deploy the NAT gateway in both Availability Zones.

![Screenshot 2023-10-24 134822](https://github.com/warlock601/AWS-public-private-Architecture-/assets/32487715/693d3869-00c7-4b26-bb16-dd8db97f096b)
