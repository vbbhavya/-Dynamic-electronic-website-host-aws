# Dynamic-electronic-website-host-aws
dynamic Website hosting using rds ec2
Dynamic Web Hosting
Create A database on RDS mysql and add source code files of website
 

Create an ec2 instance with ami Ubuntu
 
Connect to instance
And update Ubuntu with >> sudo apt-get update 
And install lamp server with command 
Sudo apt-get install lamp-server
Install git with command >> sudo apt-get install git
Install mysql client with command>> sudo apt-get install mysql-client
Changing working location to /var/www/html
Cloning git repo files >> sudo git clone <reposiority link>
Changing directory to main source code file
Accessing rds database through mysql>> mysql –h <rds endpoint> -u username –p
All command history below
 
Copy the source code of sql file for creating table
 
Now copy public ip address of ec2 and your website is live make sure to check http and https port in security group, thank you.
 
