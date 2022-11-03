
## Setting up S3


### Setting up dependencies 

- Install python3 – `sudo apt-get install python3` check version `python –version` 
- If its 2. Something then run this command: `alias python=python3` Then check the version again and it should be 3. Something.
- Install pip3 – `sudo apt install python3-pip`
- Install awscli - `sudo pip3 install awscliRun` 
- command: `aws configure` (can run this command again after filling in the details to check if they have been saved) **Enter details**: aws access key, secret key, region = eu-west-1, output = json

- Commands run after: `aws s3 ls` – to list all s3 buckets available 