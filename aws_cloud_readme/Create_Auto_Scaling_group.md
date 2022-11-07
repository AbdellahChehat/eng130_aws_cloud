# How to create an Auto Scaling Group

  1. Inside the EC2 tab, right at the very bottom, there is a tab for Auto Scaling Groups
  2. Inside there you should see a button labeled "Create Auto Scaling Group"
  3. Fill out the name of your group (follow conventions for easier use later)
4. If you do not have a launch template, create one
5. Stage 2, select your availability zones(eu-west-1a,b,c) and VPC(default for now)
6. Ensure the instance type is selected already, if you see more than the "Network" and "Instance type requirements" then you have not selected your instace type requirement while creating your template(e.g. t2.micro)
7. Stage 3, select a load balancer if you do have one
   - If not follow these steps, if you do, skip part 7
   - Click on "Attach to a new load balancer"
   - Select the appropriate balancer type (i.e. in our case Application load balancer)
   - Load balancer scheme should be "internet facing"
   - In the Health checks section, ensure to select ELB
8. In step 4, select the wanted amount for each of the categories
   - Minimum is minimum
   - Desired is usual operations amount
   - Maximum is the amount which the ASG stops creating new instances
9. Next step is to add notifications
   - Refer to Alarms section to see how to make these
   - Select the wanted notification
   - Do not worry this can be altered later
10. Tags are important, ensure to mention a "Name" tag for your ASG instances so you can clearly see and differentiate them later from other instances(follow convetions)

11. Create the group
