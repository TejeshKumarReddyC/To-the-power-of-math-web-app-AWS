# To-the-power-of-math-web-app-AWS
In this project a simple web application for calculating the exponential value of a number has been deployed in AWS by making use of AWS amplify, AWS Lambda, Dynamodb, IAM and API Gateway

# Workflow:-  Request --> Amplify --> API Gateway --> Lambda --> Dynamodb

# STEPS TO BUILD

1. Deploy the webapp files such as index.html in the AWS-Amplify (Mention your API endpoint in the code).

2. Create a lambda function and attach appropriate IAM policies to access the dynamodb.

3. Create an rest api in API Gateway and attach the lambda function as target.

4. Create a table in dynamodb.

5. Mention the table name in the lambda function's code so that it can post the data to that table.

6. Finally test the webapp with appropriate inputs. 
