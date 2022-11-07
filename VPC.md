## What is a VPC ?

- VPC stands for virtual Private cloud and it's b asically like your own private land on the cloud where you are able to launch AWS resources into a virtual network that you've defined.

## What is a Internet gateway ?

- An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet. It supports IPv4 and IPv6 traffic.

## What is a route tables ?

- Route tables are managed by routers, which act as “intersections” within the network — they connect multiple routes together and contain helpful information for getting traffic to its final destination. Each AWS VPC has a VPC router.

## CIDR Blocks ?

- A subnet CIDR reservation is a range of IPv4 or IPv6 addresses that you set aside so that AWS can't assign them to your network interfaces. This enables you to specify IPv4 or IPv6 prefixes for use with your network interfaces.

## What are subnets ? 

- A subnet is a range of IP addresses in your VPC. You launch AWS resources, such as Amazon EC2 instances, into your subnets. You can connect a subnet to the internet, other VPCs, and your own data centers, and route traffic to and from your subnets using route tables.

## What is a NACLS ?

- A network access control list (NACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets. You might set up network ACLs with rules similar to your security groups in order to add an additional layer of security to your VPC.

## DIFFERENCE BETWEEN NACLs and Security Groups? 

- Security group is a firewall on a instance level where as NACL is an added level of security on a subnet level?
