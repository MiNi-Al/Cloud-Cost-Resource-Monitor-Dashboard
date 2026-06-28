# Cloud-Cost-Resource-Monitor-Dashboard

A Python-based monitoring tool that:

Connects to AWS using boto3 (AWS SDK for Python)
Scans your AWS account and lists all running EC2 instances, S3 buckets, and their estimated costs
Checks for idle or unused resources and flags them
Generates a daily HTML report showing resource usage, cost trends, and savings recommendations
Can be scheduled to run automatically using a cron job or AWS Lambda

Tech stack to use:

Python + boto3 + AWS Free Tier (EC2, S3, Lambda, CloudWatch) + HTML report generation + cron/Lambda scheduler
