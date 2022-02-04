# web-stack-implementation

Hello and welcome to my Web Stack Implementation proejct!

What is a Web Stack? It is is a group of software components, used to implement or set up various applications (for example, a website). The "stack" refers to the specific layered components (e.g. OS system, webserver, script interpreter, and database) which are built ontop of each other. One of the most popular web stacks include LAMP, which stands for Linux, Apache, MySQL, and PHP. The LAMP stack will be used for this project! 

### **Step 0 - Prerequisites for the Web Stack Implementation project**

Before starting this project, it was necessary to set up a virtual enviornment. In order to achieve this, first, I created a free [AWS account](https://aws.amazon.com/)and then I created a virtual server using the Ubuntu Server OS.

You may be wondering, 'what is AWS'? Amazon Web Services (AWS) is the leading Cloud Service Provider in the world. AWS offers a wide variety of databases and services for different types of applications. This allows users to choose the right tool for the job while receiving the best cost and performance. 

AWS offers a Free Tier for newly registered account users. This enables users to try out some AWS services free of charge within certain usage limits. For this project, I utilized the [EC2 (Elastic Compute Cloud)](https://aws.amazon.com/ec2/features/) compute service, which is covered by the Free Tier!

Here is how I did it:

1. I began by registering and setting up an [AWS account](https://portal.aws.amazon.com/billing/signup#/start) and following the directions on the screen.

2. Once I had setup my account, I logged in as the IAM user. I navigated to the top-right of my screen and selected my preferred region (the closest to me).

3. Next, I navigated to the EC2 service, and launched an instance. I selected a Ubuntu Server 20.04 LTS (HVM) as the Amazon Machine Image (AMI)and selected a storage t2.micro as the instance type.

**Here is a video walkthrough of the aforementioned steps** 

Copy and paste the command: `sudo chmod 0400 mykeypair.pem`



### **Step 1 - ABC...**