![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/771ac9d2-88ec-48d1-bde0-a0780e3a415d)# aws-ec2-wordpress-website-deploy-method
in this repo process of creating a server and deploying the WordPress website method are discussed

first of all, as for practice, we have to create an account for AWS if we don't have it currently
then in services click ec2
then launch a new instance
type name for it
then configure according to your requirement to create a simple ec2 instance
I'll be using the Ubuntu web server 20.1 
so I'll choose it and then allow https and http to access
then create a security group(give it a simple name not use the name with symbols etc)
then launch

once launched I will open cmd on my PC 
type cd Download (to Access the security key that is downloaded )
type the command ssh -i "name of the key" ubuntu@public ip(access it by clicking the instance you're  trying to access)
if you did the step correctly, you will be able to access the Ubuntu instance through your command line 
when reached the command line 
type these commands one by one 
dot type the number in here 
2  ls -la
    3  sudo apt-get update    (for updating )
    4  sudo apt-get upgrade    (for upgrading)
    5  sudo apt-get install ec2-instance-connect    (for installing the connect package to use it)
    4  sudo apt-get upgrade  (to upgrade all packages)
   10 sudo apt-get install apache2
   
to exit Ubuntu you can use the command exit 
to get back in type the same command you accessed it (ssh -i "name of the key" ubuntu@public ip)
   to view the history of commands you typed in the ubuntu then type history and enter

to see if the Apache server is working, go to aws instances click on the instance find the public DNS below then copy and paste it into the new tab in the browser

![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/40e0144f-cfe9-43b8-98aa-2aecbbce3be3)

if you see this you did great till now 


![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/f1407b3a-9f6d-4c92-baf1-9954df51b382)

type these commands and there you go 


type public key DNS in the new web browser



![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/06dab51d-7366-4a4d-af64-c1ac37b20402)



