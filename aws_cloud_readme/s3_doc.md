
## Setting up S3


### Setting up dependencies 

- Install python3 – `sudo apt-get install python3` check version `python –version` 
- If its 2. Something then run this command: `alias python=python3` Then check the version again and it should be 3. Something.
- Install pip3 – `sudo apt install python3-pip`
- Install awscli - `sudo pip3 install awscliRun` 
- command: `aws configure` (can run this command again after filling in the details to check if they have been saved) **Enter details**: aws access key, secret key, region = eu-west-1, output = json

- Commands run after: `aws s3 ls` – to list all s3 buckets available 

# ----------------------- 
- command to create a bucket in VM `aws s3 mb s3://eng130-abdellah`

- `aws s3 cp testing-s3.txt s3://eng130-abdellah` copy file from current location and upload onto s3 bucket on aws  

- Download from bucket to local host `aws s3 cp s3://eng130-abdellah/testing-s3.txt /home/ubuntu/`
- format ``

- Delete an object inside a s3 bucket `aws s3 rm s3://eng130-abdellah/testing-s3.txt`

- How to delete a bucket completely `aws s3 rb s3://eng130-abdellah`

# S3 with Python 



