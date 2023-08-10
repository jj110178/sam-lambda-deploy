## This is a Sample SAM deploy with Lambda Function Example

This assumes tha tyou have AWS and SAM installed

1. Configure your AWS credentials using aws configure and and input your access id and secret key

1. Build the application using : ```sam build ```
1. Next is to deploy the application : ```sam deploy --guided ``` and fill out necessary prompts
1. Validate by going to your AWS Console cloud formation it should build and create your resources. 