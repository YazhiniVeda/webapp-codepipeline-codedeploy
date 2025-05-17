# Web Application Deployment using AWS CodePipeline & CodeDeploy

This project demonstrates an automated deployment pipeline for a web application using **AWS CodePipeline** and **CodeDeploy**. The solution enables continuous integration and continuous delivery (CI/CD) using native AWS services with monitoring and notifications.

## Tools & AWS Services Used

- **EC2** – Hosting the web application
- **S3** – Artifact storage
- **CodePipeline** – CI/CD pipeline orchestration
- **CodeDeploy** – Application deployment automation
- **IAM** – Role-based access control
- **SNS** – Deployment status notifications
- **CloudWatch** – Monitoring and logging

## CI/CD Workflow Overview

1. **Source Stage**: Code is pushed to a GitHub repository
2. **Build Stage** *(optional)*: Build artifacts are uploaded to an S3 bucket
3. **Deploy Stage**: CodeDeploy fetches from S3 and deploys to EC2 instances
4. **Notification Stage**: SNS sends success/failure alerts
5. **Monitoring**: CloudWatch logs provide real-time visibility

## Key Features

- Fully automated end-to-end deployment pipeline
- Real-time deployment status notifications via **SNS**
- Monitoring and log analysis using **CloudWatch**
- Secured deployments using **IAM roles and permissions**

## Outcomes

- Learned how to configure AWS CodePipeline and CodeDeploy
- Integrated version control with deployment automation
- Gained hands-on experience with cloud-native DevOps tools

## Future Improvements

- Add build stage using **AWS CodeBuild** or **Jenkins**
- Integrate with **Slack/Email notifications**
- Enable **blue/green deployment strategy**

