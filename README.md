
# Cloudformation Nested Stacks

In this project We used Cloudformation Nested Stacks to create a simple httpd application using ec2 instance and a vpc.

1. ec2.yaml is root yaml file for this project in which i nested 2 other stacks with yaml files named vpc.yaml and sg.yaml.
2. In vpc.yaml file i have created the vpc required for this application in which our application will deploy.
3. In sg.yaml i have created the security group for our ec2 instance.



## Usage/Examples



1. First we have to create a s3 bucket in our AWS account and we have to upload yaml files for vpc and security group.
 and we have to mention these URLs in our root template file ec2.yaml under the Vpc stack Template url and Sg Stack template url.

2. And after that simply we have to create the cloudformation stack using our root template file ec2.yaml and Finally after 30-40 seconds we have our stack and simple application ready.





## Few More Words :)

Try this simple cloudformation stack to create a simple application and do some hands-on on creating infrastructure as code...Thanks