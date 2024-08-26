# AWS Resource Listing Automation Script

## Overview

This shell scripting project automates the process of listing various resources in an AWS account. By using this script, users can quickly get an overview of the services and resources they have running in a specific AWS region.

## Supported AWS Services

The script supports the following AWS services:

1. EC2
2. RDS
3. S3
4. CloudFront
5. VPC
6. IAM
7. Route53
8. CloudWatch
9. CloudFormation
10. Lambda
11. SNS
12. SQS
13. DynamoDB
14. EBS

## How It Works

The script takes two arguments from the command line: the AWS region and the service name. It then uses the AWS CLI to list the resources for the specified service in the given region. If the required arguments are not provided or if an invalid service is specified, the script will display an error message and exit.

## Prerequisites

- **AWS CLI**: Make sure that the AWS CLI is installed and configured on your system. You can install it by following the official [AWS CLI installation guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).
- **AWS Credentials**: Your AWS CLI must be configured with valid AWS credentials. You can configure it using the `aws configure` command.
- **Bash Shell**: The script is designed to be run in a Bash shell environment.
