 Serverless REST API

A simple serverless REST API built with Amazon API Gateway and AWS Lambda.

 Architecture is

Client
   |
   v
API Gateway
   |
   v
POST /student
   |
   v
AWS Lambda
   |
   v
Response


 AWS Services Used

Amazon API Gateway — Receives and routes HTTP requests.
AWS Lambda — Processes the request without requiring a server.
Amazon CloudWatch — Used by AWS for Lambda monitoring and logging.

 API Endpoint

Method: POST

Resource:/student

The API was deployed through an API Gateway `prod` stage.

Sample Request

json
{
  "name": "Aisha"
}

 Sample Response

Hello! This is my serverless REST API.

 Project Workflow

1. Created an AWS Lambda function.
2. Created an API using Amazon API Gateway.
3. Created the /student resource.
4. Configured a POST method.
5. Connected API Gateway to the Lambda function.
6. Deployed the API to the prod stage.
7. Tested the API through API Gateway.
8. Tested the deployed endpoint using PowerShell.
9. Confirmed a successful response.

 What I Learned

Through this project, I practiced:

* Building a serverless API.
* Creating API Gateway resources and routes.
* Integrating API Gateway with Lambda.
* Deploying an API to a stage.
* Sending HTTP POST requests.
* Testing a live API endpoint using PowerShell.
* Understanding the request and response flow in a serverless architecture.

 Project Status

Completed ✅

This project was created as part of my AWS cloud engineering learning journey.
