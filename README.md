Cloud Cost Optimizer Bot (AWS)

Overview:
This project is an automated AWS cloud cost monitoring system that tracks daily spending and sends alerts if costs exceed a predefined threshold. Built with AWS Lambda, Cost Explorer, SNS, and EventBridge, it helps businesses optimize cloud usage and prevent unexpected bills.

Features:

Daily cost monitoring via AWS Lambda

Email alerts using SNS when spending exceeds thresholds

Automated scheduling using EventBridge

Secure IAM role configuration for AWS service access

Tech Stack:

Python

AWS Lambda

AWS Cost Explorer

AWS SNS

AWS EventBridge

Usage:

Configure environment variables (threshold, SNS topic ARN).

Deploy Lambda function with required IAM permissions.

Set up EventBridge rule for daily execution.

Receive automated cost alerts via email.

Next Steps:

Add Slack notifications

Generate detailed cost dashboards

Optimize multi-account monitoring

Purpose:
Demonstrates hands-on experience with AWS automation, cost management, and serverless architecture — ideal for portfolios and cloud-focused projects.
