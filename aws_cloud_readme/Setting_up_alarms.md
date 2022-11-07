# How to set up an Alarm

1. To create an alarm navigate to the Cloud Watch tab
2. Click on "All alarms" on the left under Alarms
3. Then Click "Create Alarm"
4. Under "Select metric"
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