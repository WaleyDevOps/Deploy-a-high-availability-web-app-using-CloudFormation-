Project 2 - Deploy-a-high-availability-web-app-using-CloudFormation
---------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/87425471/209681149-fdeeedd0-ec13-441f-af07-dab5a0476803.png)

In this project (Udagram App), I deployed web servers for a highly available web app using CloudFormation. I wrote the script that creates and deploys the infrastructure and application for an Udagram app from the ground up. The script begin deploying the networking components followed by servers, security roles, and a sample website files located in a public S3 Bucket to the Apache Web Server running on an EC2 instance.


## The files included are:
```sh
* /Images-of-result-deploy : Screenshot the result of deploy.
* /App of Udagram : Udagram App Code (It is just simple one page HTML code)
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* infraandandserver.yml : Udagram Project's CloudFormation script.
* infraandserver.json : Udagram Project's CloudFormation script parameters.
```
## Instruction of deploy:

Just run;
```sh
> ./create.sh UdagramApp infraandserver.yml infraandserver.json
```
