# aws-cloudpipline-prj
This project demonstrates how to use AWS CodeBuild and AWS CodePipeline to implement a complete CI/CD pipeline for deploying an application on AWS.

Services Used
AWS CodePipeline AWS CodeBuild Amazon EC2 GitHub (source repository)

CI/CD Flow
Code is pushed to the GitHub repository AWS CodePipeline is triggered automatically CodeBuild runs the build process using buildspec.yaml Build artifacts are generated The deployment stage invokes the CD pipeline and deploys the application.

The main goal of this project is to learn and implement AWS CI/CD using CodeBuild and CodePipeline in a real-world deployment scenario.
