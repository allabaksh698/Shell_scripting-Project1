# AWS Resource Listing Automation Script

## Overview

This project provides a shell script that automates the process of listing resources in an AWS account. The script supports multiple AWS services, allowing users to quickly retrieve information about their cloud infrastructure. This can be especially useful for auditing, monitoring, or managing resources across various AWS services.

## Features

- Lists resources from different AWS services such as EC2, S3, RDS, IAM, and more.
- Supports specifying the AWS region and service as input parameters.
- Checks for AWS CLI installation and configuration before execution.
- Provides clear error messages and usage instructions.

## Supported AWS Services

The script can list resources for the following AWS services:

1. EC2
2. RDS
3. S3
4. CloudFront
5. VPC
6. IAM
7. Route53
8. Lambda
9. SNS
10. SQS
11. DynamoDB
12. EBS

## Prerequisites

- AWS CLI installed and configured on the machine.
- Appropriate IAM permissions to access the AWS resources.
- Bash shell environment.
