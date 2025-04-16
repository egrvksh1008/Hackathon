AWS Fargate Deployment Track
Objective
Deploy the containerized microservices using AWS Fargate, demonstrating your skills in container orchestration, serverless computing, and AWS services.

Technical Requirements
Infrastructure as Code (Terraform)

Provision a VPC with public and private subnets
Set up an ECS cluster with Fargate launch type
Configure necessary IAM roles and security groups
Set up an ECR repository for your container images
Create an Application Load Balancer
Containerization

Create a Dockerfile for the microservices
Build and push the Docker image to ECR
ECS/Fargate

Create ECS task definitions
Set up ECS services for your applications
CI/CD (GitHub Actions)

Implement a workflow for Terraform (lint, plan, apply)
Create a workflow for building and pushing Docker images
Implement a workflow for deploying to ECS/Fargate
Monitoring and Logging

Set up CloudWatch for container insights and application logging
(Bonus) Implement custom CloudWatch dashboards
Deliverables
GitHub repository containing:

Terraform code
Dockerfiles
ECS task definitions
GitHub Actions workflows
Application code (provided microservices)
Documentation:

Architecture diagram
Setup and deployment instructions
Monitoring and logging overview
Evaluation Criteria
Fargate cluster configuration and security
ECS task and service management
CI/CD pipeline efficiency and reliability
IaC quality and modularity
Containerization best practices
Monitoring and logging effectiveness
Documentation clarity and completeness
Back to main page
