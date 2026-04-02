# AWS Serverless Task API

## Overview
This project is a serverless REST API built using AWS. It allows users to create and retrieve tasks through HTTP requests. The system is fully deployed in the cloud and designed using modern serverless architecture principles.

## Architecture
- **API Gateway** – Handles incoming HTTP requests
- **AWS Lambda** – Executes backend logic
- **DynamoDB** – Stores task data (NoSQL database)

## Features
- Create tasks (POST request)
- Retrieve tasks (GET request)
- Fully serverless and scalable
- Deployed in AWS cloud environment

## Example Usage

### Create Task (POST)
```json
{
  "task": "Learn AWS"
}
