# AWSSkillBuilder
Tests and notes for AWS Skill Builder Course.

# Introduction
The Cloud Quest begins with an introduction as a Cloud Practitioner Role where we are going to be introduced to AWS services and we will build basic AWS solutions based on several business rules.

## Cloud Computing Essentials
The first task that is given to us is to migrate the beach wave site prediction page to AWS to improve its reliability.

### Objectives
As objectives, we will be able to:
- Articulate the characteristics of the AWS cloud computing platform
- Describe the core benefits of using AWS products and services
- Compare and contrast AWS cloud services to On-Premises infraestructure
- Implement hosting a static web page using Amazon S3

### Video Concepts
Firstly, we are going to be in context with the usage of an S3 Bucket and its benefits.
![image](https://user-images.githubusercontent.com/16247985/159351941-d6cca5ab-68c0-4773-bccd-f8d238f63341.png)

![image](https://user-images.githubusercontent.com/16247985/159352427-0e745494-4fa4-4dfa-be01-7d8e84ea40cd.png)

![image](https://user-images.githubusercontent.com/16247985/159352576-644a8df0-a411-4c6d-8c1e-25201867370d.png)

Then, we are going to explore the features that S3 provides us.
![image](https://user-images.githubusercontent.com/16247985/159353062-69d2a093-0598-46d0-a2fc-427c43dc564a.png)

![image](https://user-images.githubusercontent.com/16247985/159353874-4a6f579a-dbfa-424a-a099-9c5614f90c41.png)

![image](https://user-images.githubusercontent.com/16247985/159354385-5f974079-eb97-4c56-9078-a81d96820e87.png)

Identifying access management
![image](https://user-images.githubusercontent.com/16247985/159354816-11748ae5-455c-4e06-a7e6-840f7c9a9168.png)

![image](https://user-images.githubusercontent.com/16247985/159355238-d3df7cc6-d239-48e4-8672-7a1e23f45579.png)

![image](https://user-images.githubusercontent.com/16247985/159355547-3f264ad9-6b23-430b-aa4e-d17735755318.png)

Reviewing performance
![image](https://user-images.githubusercontent.com/16247985/159355719-46b16ea6-a992-46a4-880f-c4b3eee992c9.png)

![image](https://user-images.githubusercontent.com/16247985/159355913-a4acfca3-d368-4506-b7d9-aa3cbee8467b.png)

![image](https://user-images.githubusercontent.com/16247985/159356088-b16007aa-0917-4af1-81b6-bc1db4f5ce41.png)

![image](https://user-images.githubusercontent.com/16247985/159356282-1f9fa95f-b7e1-4005-99d7-a1115bb957a9.png)

Now, we will check the types of cloud computing
![image](https://user-images.githubusercontent.com/16247985/159356904-6ac2b019-34bd-49ff-bf78-032096b271d8.png)

![image](https://user-images.githubusercontent.com/16247985/159357374-f8f59d5a-8e0b-4d8a-be6e-12515a865831.png)

![image](https://user-images.githubusercontent.com/16247985/159357840-9537e01b-1fb9-4956-91b9-5c46feaa35d4.png)

Deployment models
![image](https://user-images.githubusercontent.com/16247985/159358576-abb3d424-2d4c-4f56-841f-5b3f50ae23cf.png)


### Business Rules
Now, we have the following business rules:
- The data center powers most of the technical infrastructure but it takes too long to configure it.
- The page is static

### Building the solution
As a solution, we propose to use an AWS infrastructure, which is easier and faster to configure and adapt to the client, mostly because it's a service on-demand. Also, the deployments are done in a matter of minutes. Since the page is static, we can create an S3 bucket to configure, host and run the page.

The steps to build the solution goes as follows:
- Create an S3 bucket
- Configure the S3 Bucket Hosting
- Upload the static files to host the site
- Rename index.html to waves.html

![image](https://user-images.githubusercontent.com/16247985/159359392-98ff4563-cc30-4e06-8fe6-36b34d98c21e.png)

![image](https://user-images.githubusercontent.com/16247985/159359639-cd02a74b-3791-4438-a4cb-ce227939c1d1.png)

![image](https://user-images.githubusercontent.com/16247985/159359729-627014d2-c78e-4063-94ae-e25905894e38.png)

![image](https://user-images.githubusercontent.com/16247985/159360128-7aca3bb9-40f4-4fda-a3c7-68e0975ae1d1.png)

![image](https://user-images.githubusercontent.com/16247985/159360219-323b8ade-7121-4d98-a778-7e88da4112d6.png)

![image](https://user-images.githubusercontent.com/16247985/159360741-46b0da09-dc62-4f1f-86ed-85ab2f1801d5.png)

![image](https://user-images.githubusercontent.com/16247985/159361006-a10537e7-bf3c-4d6c-9644-8e061f72287c.png)

![image](https://user-images.githubusercontent.com/16247985/159361262-d2ed29fc-d24f-44f9-86c8-2bdf47785d53.png)

![image](https://user-images.githubusercontent.com/16247985/159361674-78754a2d-b5fa-46c1-844d-ac60f1bd03c6.png)

![image](https://user-images.githubusercontent.com/16247985/159361712-88275f05-f353-438f-881b-84de8e5e15e9.png)

![image](https://user-images.githubusercontent.com/16247985/159362066-916cc34e-a38c-4d66-b7e0-03a62c264bd5.png)

![image](https://user-images.githubusercontent.com/16247985/159363318-30ad2a1d-0e68-4360-802a-357bf4b2b30e.png)

![image](https://user-images.githubusercontent.com/16247985/159363978-a20e1d92-7e85-4019-9b9c-80224fa54fe8.png)












