# How to create an Auto Scaling Group

  1. Inside the EC2 tab, right at the very bottom, there is a tab for Auto Scaling Groups
  <img width="215" alt="Screenshot 2022-11-07 at 09 35 28" src="https://user-images.githubusercontent.com/115224560/200276849-2f473015-80dc-45ad-97dc-26fd8a74e6ee.png">

  2. Inside there you should see a button labeled "Create Auto Scaling Group"
  <img width="1096" alt="Screenshot 2022-11-07 at 09 35 35" src="https://user-images.githubusercontent.com/115224560/200276965-29e4f386-0233-4974-a47c-eceec75feeea.png">

  3. Fill out the name of your group (follow conventions for easier use later)
<img width="1147" alt="Screenshot 2022-11-07 at 09 35 42" src="https://user-images.githubusercontent.com/115224560/200277027-d299e230-212c-4b87-9a2d-1741e41c812a.png">

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
