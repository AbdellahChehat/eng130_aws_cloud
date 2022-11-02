# How to create EC2 Instance 

- Step 1: Navigate to Launch Instance 
- Step 2: Configure the EC2 appropiately: see Images below..

<img width="799" alt="Screenshot 2022-11-02 at 08 53 49" src="https://user-images.githubusercontent.com/115224560/199455924-ba50cd0d-c450-417e-a478-c987cd30d084.png">
<img width="737" alt="Screenshot 2022-11-02 at 09 36 34" src="https://user-images.githubusercontent.com/115224560/199455958-87950c08-ef17-4f2b-9451-c48f429ac066.png">
<img width="800" alt="Screenshot 2022-11-02 at 09 36 47" src="https://user-images.githubusercontent.com/115224560/199455988-dead2ddf-c839-4e68-83a9-5a08a3131154.png">


- Step 3: Onced its launched click on `connect`
- Step 4: Inside Connect click on `SSH Client`
- Image below...
  
<img width="858" alt="Screenshot 2022-11-01 at 16 55 50" src="https://user-images.githubusercontent.com/115224560/199300581-53c21b67-ae5e-4ffa-81a5-38af487092d0.png">



# How to connect to the Instance using Terminal

- Select the Instance you want to connect to `eng130_abdellah`
- Go to `SSH client` on AWS 
- Copy the example given e.g `ssh -i "eng130.pem" ubuntu@ec2-34-245-4-146.eu-west-1.compute.amazonaws.com` 
- Go to your terminal and run this command `cd ~/.ssh`
- Then paste the example you copied
- You will now be connected to the VM
  
