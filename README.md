# Project
A simple Jenkins CI/CD application deployment pipeline to Kubernetes on the AWS infrastructure. Automated with Terraform 

# Overview
Developers commit code to a Git repository, triggering Jenkins to initiate a build process. Jenkins compiles the Java code into an executable WAR file. This WAR file is then packaged with Tomcat into a Docker image and subsequently pushed to Amazon Elastic Container Registry (ECR). Following this, Jenkins employs Terraform to provision an Amazon Elastic Kubernetes Service (EKS) cluster, deploying the Docker image into the cluster. Once deployed, users can conveniently test the application using a web browser.

<img src="https://github.com/profebass99/jenkins-terraform-eks/assets/104143346/3f52921a-da83-46fd-8f6e-628de6695421" width="5800">

# Requirements
AWS Infrastructure
VPC following AWS best practice with public and private subnets
Jenkins (Terraform)
GitOps or equivalent
EKS on AWS

![jenkins-pipeline.png](./jenkins-pipeline.png)

### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com) 

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License

*  Nho Luong (c) 2024
