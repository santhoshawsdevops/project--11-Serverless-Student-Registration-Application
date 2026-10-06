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



Student registered successfully!

Student ID: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
