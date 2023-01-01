Project 2 - Deploy-a-high-availability-web-app-using-CloudFormation
---------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/87425471/209681149-fdeeedd0-ec13-441f-af07-dab5a0476803.png)

> In this project (Udagram App), I deployed web servers for a highly available web app sitting behind a Loadbalancer in a private subnets using CloudFormation.
> A simple script that creates and deploys the infrastructure and application for an Udagram app was written. The script begin the deployment in sequence, starting with the networking components followed by servers, security roles, and a sample website files located in a public S3 Bucket to the Apache Web Server running on an EC2 instance.


## The folders and files included are:
```sh
* /screenshots : Screenshot the result of deploy.
* /UdagramApp : Udagram App Code (It is just simple one page HTML code)
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* infraandandserver.yml : Udagram Project's CloudFormation yaml file.
* infraandserver.json : Udagram Project's CloudFormation json parameters.
```
## To create the stack:

Just run;
```sh
 ./create.sh MyProject-UdagramApp infraandserver.yml infraandserver.json
```

## NOTE
```sh
* The ssh public key was not included as instructed in the requirement.