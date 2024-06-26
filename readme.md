## Automated Deployment of a Two-Tier AWS Infrastructure

![image](https://github.com/RETAJD/Automated-deployment/assets/45774493/0b700ac2-a480-45ba-a7cc-6cbf694ee5dd)

## Required to automate the deployment of a two-tier infrastructure on AWS, consisting of a web server (EC2 instance) and a SQL database (RDS). The deployment process should leverage Infrastructure as Code (IaC) principles and be executed through a CI-CD pipeline

# Requirements

#### Web Server

Type: AWS EC2 Instance
OS: Linux

#### Application: WordPress (Download – WordPress.org) installed and configured

#### Accessibility: Publicly accessible (HTTP initially, with HTTPS implementation earning extra points)

#### Security: Located in a public subnet; security group allowing only necessary traffic (HTTP or HTTPS)

## Database

Type: AWS RDS (MySQL or PostgreSQL)
Accessibility: Hosted in a private subnet
Security: Security group configured to allow connections only from the web server on required ports

## CI-CD Pipeline

Automation of the entire deployment process
Use of AWS CloudFormation templates to define and create the infrastructure components
Infrastructure as Code (IaC):
All infrastructure components must be defined and managed as code

## Visibility and Accessibility

The default WordPress website should be visible and accessible from the public internet
Security and Network Configurations:
Proper configuration of security groups and subnets to ensure secure access
HTTPS implementation is optional but preferred for additional points

## Success Criteria

Successful deployment of a functional two-tier architecture (web server and database) in AWS, automated via CI-CD pipeline.
WordPress site is publicly accessible and operational.
Compliance with specified security and network configurations.
