# Automated Cost Optimizer

## Project Overview
AWS automation project for reducing cloud costs by automatically monitoring and managing unused EC2 resources.

## AWS Services Used
- AWS Lambda
- Amazon CloudWatch
- Amazon EC2
- boto3

## Features
- Automatic monitoring of EC2 usage
- Stop unused EC2 instances automatically
- Scheduled automation using CloudWatch
- Reduce unnecessary AWS costs
- Serverless automation using Lambda

## Tech Stack
- Python
- boto3
- AWS Cloud Services

## Architecture
CloudWatch Trigger → AWS Lambda → EC2 Management

## Purpose
This project helps reduce AWS bills automatically by identifying and stopping idle EC2 instances using AWS Lambda automation.

## Setup Steps
1. Configure AWS CLI
2. Install boto3
3. Create Lambda function
4. Add EC2 optimization script
5. Configure CloudWatch trigger
6. Deploy and test automation

## Install Dependencies
```bash
pip install boto3
