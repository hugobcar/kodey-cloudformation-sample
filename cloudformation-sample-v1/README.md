# CloudFormation Sample V1

This CloudFormation template is designed to implement a scenario involving AWS services such as API Gateway, Lambda, SQS, DynamoDB, RDS, and S3. The process flow is as follows:

1. An API Gateway is created to trigger a Lambda function.
2. The Lambda function sends data to an SQS queue.
3. The SQS queue triggers another Lambda function, which sends the data to both DynamoDB and RDS.
4. Both DynamoDB and RDS are connected to an S3 bucket used for data storage.
5. Finally, the data is sent back to the API Gateway.

This template includes the necessary resources and configurations for the scenario.