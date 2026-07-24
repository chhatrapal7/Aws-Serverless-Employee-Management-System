## Live Demo

The application was successfully deployed and tested on AWS.
The live deployment is currently unavailable because the infrastructure was created using the AWS Free Tier and has been stopped to avoid ongoing charges.
Architecture diagrams and project screenshots are included in this repository.

## Project Overview

This project demonstrates a complete AWS Serverless Employee Management System built using an event-driven architecture.
The frontend is hosted on Amazon S3 and communicates with backend HTTP APIs exposed through Amazon API Gateway. Employee registration requests are processed asynchronously using Amazon SQS and AWS Lambda before being stored in Amazon DynamoDB. Employee records are retrieved from DynamoDB through a separate Lambda function.


## Architecture


## AWS Services Used

| Service            | Purpose            |

| ------------------ | ------------------ |

| Amazon S3          | Frontend Hosting   |

| Amazon API Gateway | REST APIs          |

| AWS Lambda         | Serverless Compute |

| Amazon SQS         | Message Queue      |

| Amazon DynamoDB    | NoSQL Database     |

| Amazon CloudFront  | CDN                |

| Amazon Route 53    | Custom Domain      |

| AWS IAM            | Permissions        |

| Amazon CloudWatch  | Logs & Monitoring  |


## Workflow

User
   │
   ▼
Amazon S3
   │
   ▼
API Gateway
   │
   ▼
Lambda Producer
   │
   ▼
Amazon SQS
   │
   ▼
Lambda Consumer
   │
   ▼
Amazon DynamoDB
   │
   ▼
GET API
   │
   ▼
Frontend



## Features
Serverless Architecture
Event-driven Processing
Amazon API Gateway HTTP API
Asynchronous Messaging using Amazon SQS
AWS Lambda Integration
Amazon DynamoDB
CloudFront Distribution
Route 53 Custom Domain
CloudWatch Monitoring


## Skills Demonstrated
Amazon S3
Amazon API Gateway (HTTP API)
AWS Lambda
Amazon SQS
Amazon DynamoDB
Amazon CloudFront
Amazon Route 53
IAM
CloudWatch
Event-driven Architecture
Serverless Computing


## API Endpoint 
| Method | Endpoint     | Purpose                 |
| ------ | ------------ | ----------------------- |
| POST   | /register  | Register a new employee |
| GET    | /employees | Retrieve all employees  |



## Connect with Me

** Chhatrapal Janghel **

AWS Cloud | DevOps | Multi-Cloud 

- LinkedIn: www.linkedin.com/in/chhatrapaljanghel7

- Portfolio: https://chhatrapal.in


