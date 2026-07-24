## Live Demo

The application was successfully deployed and tested on AWS.
The live deployment is currently unavailable because the infrastructure was created using the AWS Free Tier and has been stopped to avoid ongoing charges.
Architecture diagrams and project screenshots are included in this repository.

## Project Overview

This project demonstrates a complete AWS Serverless Employee Management System built using event-driven architecture. The application allows users to register employees through a web interface hosted on Amazon S3. Employee requests are processed asynchronously using Amazon SQS and AWS Lambda before being stored in Amazon DynamoDB. Users can also retrieve and view all employee records through REST APIs exposed by Amazon API Gateway.


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


