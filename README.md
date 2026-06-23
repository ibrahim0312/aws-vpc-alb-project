# AWS Highly Available Web Application

## Project Overview

This project demonstrates the deployment of a highly available web application on AWS using core AWS services.

## Services Used

* Amazon VPC
* Amazon EC2
* AWS IAM
* Amazon S3
* Application Load Balancer (ALB)
* Target Groups
* Security Groups

## Architecture

Internet → Application Load Balancer → EC2 Instances

EC2 Instances → IAM Role → Amazon S3

## Implementation Steps

1. Created a Custom VPC (10.0.0.0/16)
2. Created Public Subnet-1 in ap-south-1a
3. Created Public Subnet-2 in ap-south-1b
4. Attached Internet Gateway
5. Configured Public Route Table
6. Launched Ubuntu EC2 Instances
7. Installed and configured Apache Web Server
8. Created IAM Role for EC2
9. Created and tested S3 Bucket access
10. Created Target Group
11. Created Application Load Balancer
12. Configured Health Checks
13. Tested Failover by stopping one EC2 instance

## Results

* Successfully deployed a highly available web application.
* Verified load balancing across multiple Availability Zones.
* Verified EC2 to S3 access using IAM Roles.
* Demonstrated failover and health check functionality.

## Author

Shaik Tameem Ibrahim
AWS & DevOps Engineer
