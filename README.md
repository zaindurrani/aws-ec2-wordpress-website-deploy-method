# aws-ec2-wordpress-website-deploy-method
in this repo process of creating a server and deploying WordPress website method are discussed

first of all as its for practice, we have to create account of aws if we dont have it currently
then in services click ec2
then launch new instance
type name for it
then configure according to your requirement to create a simple ec2 instance
ill be using the ubuntu web server 20.1 
so ill choose it and then allow https and http to access
then create a security group(give it a simple name not use the name with symbols etc)
then launch

once launched i will open cmd on my pc 
type cd Download (to Access security key that is downloaded )
type the command ssh -i "name of the key" ubuntu@public ip(access it by clicking the instance your  trying to access)
if you did the step correctly , you will be able to access the ubuntu instance through your command line 
when reached the command line 
type these commands one by one 
dot type the number in here 
2  ls -la
    3  sudo apt-get update    (for updating )
    4  sudo apt-get upgrade    (for upgrading)
    5  sudo apt-get install ec2-instance-connect    (for installing the connect package to use it)
    4  sudo apt-get upgrade  (to upgrade all packages)
   10 sudo apt-get install apache2
   
to exit the ubuntu you can use the command exit 
to get back in type same command you accessed it (ssh -i "name of the key" ubuntu@public ip)
   to view the history of commands yoyu typed in the ubuntu then type history and enter

to see if apache server is wowrking , go to aws instances click on the instance and find the public dns below then copy it and paste it in the new tab in browser

![image](https://github.com/zaindurrani/aws-ec2-wordpress-website-deploy-method/assets/96332173/40e0144f-cfe9-43b8-98aa-2aecbbce3be3)

if you see this you did greate till now 



