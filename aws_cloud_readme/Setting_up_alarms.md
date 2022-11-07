# How to set up an Alarm

1. To create an alarm navigate to the Cloud Watch tab


2. Click on "All alarms" on the left under Alarms
<img width="265" alt="Screenshot 2022-11-07 at 10 08 01" src="https://user-images.githubusercontent.com/115224560/200284017-11bd6a4c-c02b-4e9c-8cfb-b3653b7d7858.png">


3. Then Click "Create Alarm"
<img width="1158" alt="Screenshot 2022-11-07 at 10 08 11" src="https://user-images.githubusercontent.com/115224560/200284039-365e7316-3a93-4dcf-8015-0b40343a34c2.png">


4. Under "Select metric"
<img width="1059" alt="Screenshot 2022-11-07 at 10 08 28" src="https://user-images.githubusercontent.com/115224560/200284123-a2deb0bf-259c-46ad-a7d1-7a25c6a7612e.png">

   - Select EC2
   - Select "By Auto Scaling Group"
   - Search for your ASG and select the wanted alarm trigger (e.g. CPU utilisation)

   - Provide details
        - Threshold value is a percentage (although example is for some reason 1000)
    - Step 2
        - Select "In alarm"
        - Select or create an existing topic
    - Step 3
        - Name the alarm and add any extra message as this will be emailed to you
    - Review all details and ensure all provided date is correct
    - Create your alarm
