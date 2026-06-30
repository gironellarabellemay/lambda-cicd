# Lambda CI/CD Project

A Cloud Engineer Academy project demonstrating how to automate AWS Lambda deployments using GitHub Actions and CloudFormation.

This project helped me practise CI/CD concepts, AWS Lambda deployment workflows and troubleshooting IAM permissions during automated deployments.

## Project Overview

The goal of this project was to build a deployment pipeline where changes to Lambda code can be pushed through GitHub and deployed using an automated workflow.

The repository includes Lambda function code, CloudFormation infrastructure templates and GitHub Actions workflows.

## What This Project Demonstrates

* Building a basic CI/CD workflow with GitHub Actions
* Deploying AWS Lambda function code through automation
* Organising Lambda code and infrastructure files in a repository
* Using CloudFormation to define AWS resources
* Troubleshooting deployment issues from GitHub Actions logs
* Understanding IAM permissions needed for deployment workflows
* Practising Git-based development and automated deployment principles

## Technologies Used

* AWS Lambda
* AWS CloudFormation
* GitHub Actions
* Python
* IAM
* Git and GitHub
* VS Code
* Command Line / Terminal

## Repository Structure

```text
lambda-cicd/
├── .github/
│   └── workflows/          # GitHub Actions workflow files
├── cloudformation/         # CloudFormation templates
├── lambda/                 # Lambda function code
└── README.md
```

## Key Learning Outcomes

Through this project, I practised how to:

* Use GitHub Actions to automate deployment steps
* Package and deploy Lambda code from a repository
* Read workflow logs to diagnose failed deployments
* Fix issues caused by incorrect resource names or permissions
* Understand the connection between source control and cloud deployment
* Work with AWS IAM permissions in a deployment context

## Challenges I Worked Through

During the project, I had to troubleshoot deployment issues including function name mismatches and IAM permission problems. This helped me understand that DevOps work is not only about writing workflow files, but also about reading logs, testing assumptions and methodically fixing errors.

## Why This Project Matters

This project is relevant to cloud, DevOps and platform engineering because it shows how application changes can be delivered through an automated pipeline rather than through manual deployment steps. It also helped me understand how CI/CD workflows interact with AWS services.

## Future Improvements

* Add screenshots of successful GitHub Actions workflow runs
* Add a simple architecture diagram
* Add test steps before deployment
* Improve IAM permissions using least-privilege principles
* Add environment-specific deployment stages
