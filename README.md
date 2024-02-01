Deploying a WordPress Website on an AWS EC2 Instance

Prerequisites:

An active AWS account
Basic familiarity with Linux command-line interface
Steps:

Create an EC2 Instance:

Navigate to the AWS Management Console and select Services > EC2.
Click Launch Instances.
Choose an AMI (Amazon Machine Image) that suits your needs. For this guide, we'll use Ubuntu Server 20.1.
Select an instance type that aligns with your website's resource requirements.
Configure security groups:
Allow inbound traffic on ports 80 (HTTP) and 443 (HTTPS).
Assign a descriptive name to the security group (e.g., "WordPress-SG").
Launch the instance.
Connect to the Instance:

Locate the public IP address of your instance in the EC2 Dashboard.
Download the key pair file (.pem) associated with your instance.
Open a terminal or command prompt on your local machine.
Navigate to the directory containing the key pair file: cd Downloads
Connect to the instance using SSH: ssh -i "key-pair-name.pem" ubuntu@public-ip
Update and Install Packages:

Once connected, execute the following commands:

Bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install ec2-instance-connect apache2
Use code with caution. Learn more
Configure Apache:

(Instructions on configuring Apache for WordPress will be provided here.)
Deploy WordPress:

(Detailed steps for deploying WordPress will be outlined here.)
Access the Website:

Obtain the public DNS of your instance from the EC2 Dashboard.
Paste the public DNS into a web browser to access your WordPress website.
Additional Notes:

To exit the Ubuntu instance, use the command exit.
To view command history within the instance, use history.
For a more comprehensive guide on deploying WordPress, consult the official WordPress documentation.

![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/40e0144f-cfe9-43b8-98aa-2aecbbce3be3)

if you see this you did great till now 


![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/f1407b3a-9f6d-4c92-baf1-9954df51b382)

type these commands and there you go 


type public key DNS in the new web browser



![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/06dab51d-7366-4a4d-af64-c1ac37b20402)



