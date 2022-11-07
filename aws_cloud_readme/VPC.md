# VPC steps 

- Step 1: Create a VPC 10.0.0.0/16
- Step 2: Create an Internet gateway 
    - 2:1: Attach the IG to our VPC
- Step 3: Create a public subnet 10.0.2.0/24
- Step 4: Create a route table. - attach to VPC
    - 4:1 add routes to connect to IG 0.0.0.0/0
    - 4:2 Associate RT to public Subnet 
- step 5: Launch New ec2 


### How to Create a VPC 

1. Navigate to VPC on AWS as shown below.

2. Click on `Create VPC`

3. Select `VPC ONLY` 

    - Select `IPv4 CIDR manual input`
    - Enter `IPv4 CIDR`
    - Add tag
    - Click `Create VPC`
  
### Create Internet gateway

1. Select `VPC > Internet gateway`
2. Enter Name tag
3. click `Create Intenert gateway`
   
### Attach Internet gateway to VPC
- On `Internet gateway` click ` Action > Attach to VPC`


## How to create a subnet (private/public) 

1. Select VPC 
2. Enter a `subnet name` appropiately depending if it's private or public.
3. Availability Zone `no preference`
4. Enter `IPv4 CIDR block`
5. Clcik `Create Subnet`
   

## Create Route Table 

1. Navigate to route table `VPC > Route Table`
2. Inside route table..
    - Enter route table name
    - Select `VPC` 
    - add tag
    - Click `Create Route table`
- You'll have to create a route table for both private and public subnets 

## Public subnet config

- For the public subnet you'll have to connect it to internet as well as Associate RT to public Subnet 
- As shown below 

---

#### Once both subnets have been created and configured Start the app EC2 instance inside the public subnet and the db insatance inside the private subnet.
---
## How to launch a EC2 instance inside a subnet in a VPC

1. On EC2 click `Launch Instance`
2. Add `name` `Select appropiate AMI` `Key pair` as normal
   
3. For network setting select VPC created and then appropiate subnet `public subnet for app instance` and `Private subnet for db`
4. See below image for config 
5. In user data add 
   ```

   ```
6. Click Create EC2 Insatnce 

---
**Now that the EC2s have been launched make sure the following config is correct on the security group for both instances**

---

### App EC2 security group

### DB EC2 security group
