# AWS Cloud Resource Monitoring and Cost Optimization

A production-oriented AWS monitoring and cost optimization platform that continuously monitors cloud resources, analyzes utilization metrics, identifies underutilized services, and provides actionable recommendations to reduce AWS spending.

## 🚀 Features

* Real-time monitoring of AWS resources (EC2, S3, RDS, Lambda, EBS)
* Resource utilization tracking using Amazon CloudWatch
* Service-wise cost analysis using AWS Cost Explorer API
* Detection of idle and underutilized resources
* Automated cost-saving recommendations and estimated savings
* Email notifications and alerts using Amazon SNS
* Interactive dashboard for monitoring resource health and costs
* Containerized deployment using Docker
* Infrastructure automation using AWS CLI and CloudFormation

## 🛠️ Tech Stack

* **Cloud:** AWS (EC2, S3, RDS, Lambda, DynamoDB, IAM, CloudWatch, SNS, Cost Explorer)
* **Programming:** Python, Bash
* **DevOps:** Docker, GitHub Actions
* **Backend:** Flask, Boto3
* **Database:** DynamoDB / MySQL
* **Monitoring:** Amazon CloudWatch
* **Version Control:** Git & GitHub

## 📌 Key Functionalities

* Monitor resource utilization and performance metrics
* Generate rightsizing recommendations for EC2 and RDS instances
* Detect unattached EBS volumes and obsolete snapshots
* Identify S3 lifecycle optimization opportunities
* Calculate estimated monthly savings from optimization actions
* Send proactive alerts and recommendations via email

## 🎯 Project Goal

To help organizations improve cloud visibility, optimize AWS resource utilization, and reduce operational costs through intelligent monitoring, automation, and data-driven recommendations.

## 📈 Sample Recommendations

* Stop or downsize EC2 instances with consistently low CPU utilization.
* Delete unattached EBS volumes and old snapshots.
* Move infrequently accessed S3 objects to Intelligent-Tiering or Glacier.
* Right-size underutilized RDS instances to lower-cost configurations.
* Receive estimated monthly savings and optimization reports automatically.
