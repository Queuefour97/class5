Log into AWS Account
Preliminary Steps
1.	Log into your AWS Account
2.	Navigate to the console and make note of the Region you are going to use
3.	Navigate to the EC2 Dashboard
Step 1: Create Security Group
1.	From the left column, choose Network and Security -> Security Groups
2.	Choose:  “Create Security Group”
3.	Input the Security Group Name and the Description
4.	The VPC should be set to default
5.	Inbound HTTP rule should be “Anywhere IPv4”
6.	Source should me (0.0.0.0/0)
7.	DO NOT touch or change the Outbound Rules
8.	Choose “Create Security Group”
9.	Verify all settings are correct (check work)
Step 2: Obtain startup script from Theo or Aaron McDonald’s GitHub
1.	Copy GitHub Script
Step 3: Launch EC2 Instance
