# auth-lambda

Serverless authentication with DynamoDB and the Chalice framework on AWS Lambda.

## Running locally

1. Create your environment with:
   `pipenv install --dev`

2. Start the DynamoDB container
   `docker run -p 8000:8000 amazon/dynamodb-local`

3. Start Chalice
   `cd auth-lambda && pipenv run chalice local`
