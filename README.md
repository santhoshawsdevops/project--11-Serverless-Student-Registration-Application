# Serverless Student Registration Application

## Project Overview

A serverless student registration application built using AWS services.
Users enter their name, email and age through a web interface.
The request is sent to API Gateway, processed by AWS Lambda,
and stored in Amazon DynamoDB.

## Architecture

S3
 ↓
API Gateway
 ↓
AWS Lambda
 ↓
DynamoDB


## AWS Services Used

- Amazon S3
- Amazon API Gateway
- AWS Lambda
- Amazon DynamoDB
- AWS IAM


## Application Flow

1. User opens the frontend .
2. User enters student information.
3. Frontend sends a POST request to API Gateway.
4. API Gateway invokes Lambda.
5. Lambda processes the request.
6. Lambda stores the student information in DynamoDB.
7. Lambda returns a success response.

##Project description

* Built a serverless student registration application using Amazon S3, API Gateway, AWS Lambda, and DynamoDB.
* Developed a Python-based Lambda function to process student registration requests and store data in DynamoDB.
* Hosted the frontend using Amazon S3 and integrated it with API Gateway through HTTP requests.
* Configured IAM permissions for secure communication between AWS services and used CloudWatch for Lambda execution logs.
* Tested and troubleshot the complete request flow from frontend → API Gateway → Lambda → DynamoDB

Student registered successfully!

Student ID: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
