# Myportfolio_Serverless
This is Serverless portfolio, S3, Lambda and API Gateway

1. Create Serverless Web

S3: Create Static Website
Route 53: register domain and Alias Target to S3
Lambda: -(Role:Simple microservice permissions let Lambda to work)
        -Function Code
        -Add Triggers API Gateway
API Gateway: -Create Method Get method-Lambda
             -Create Deployment

2. Version Control with lambda
## you can publish one or more versions of your Lambda function. You can work with different variations of your Lambda function
## &LATEST = latest function Code, Qualified
