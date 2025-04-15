Prerequisites
AWS account
Source
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html
![alt text](Capture0-1.PNG)
Step 1: **Launch an instance**
1. Open the Amazon EC2 console
2. You can use the selected Region, or optionally select a Region that is closer to you.
3. From the EC2 console dashboard, choose Launch instance.
![alt text](Capture1-1.PNG)
4. Under Name and tags, for Name, enter a descriptive name for your instance.
5. Under Application and OS Images, Choose Quick Start, and then choose the operating system (OS) for your instance.
6. From Amazon Machine Image (AMI), select an AMI that is marked Free Tier eligible.
![alt text](Capture2-1.PNG)
7. Under Instance type, for Instance type, choose t2.micro, which is eligible for the Free Tier. In Regions where t2.micro is not available, t3.micro  is eligible for the Free Tier.
8. Under Key pair name, choose an existing key pair or choose Create new key pair to create your first key pair. For this, I used an existing key pair I had created previously.
![alt text](Capture3-1.PNG)
9. Under **Network settings**, for your first instance, you can use the default settings.
![alt text](Capture4-1.PNG)
10. Under Configure storage, you can use the configured root volume but no data volumes. This is sufficient for test purposes.
11. choose **Launch instance**.
![alt text](Capture5-1.PNG)
![alt text](Capture6-1.PNG)
Success!
12. Select the checkbox for the instance.
13. The initial instance state is pending. After the instance starts, its state changes to running.
![alt text](Capture7-1.PNG)

Step 2: Connect to your instance
The procedure that you use depends on the operating system of the instance.
![alt text](Capture8-1.PNG)
![alt text](Capture9-1.PNG)
I will be connecting via the EC2 instance connect. For a more secure connection, you can connect via session manager but that will involve assigning a role. For our test purpose, this will do.
![alt text](Capture10-1.PNG)
Success!

Step 3: Clean up your instance
Select your created instance and right click.
Choose Terminate instance
![alt text](Capture11-1.PNG)
![alt text](Capture12-1.PNG)
![alt text](Capture13-1.PNG)
The Instance has been terminated successfully.