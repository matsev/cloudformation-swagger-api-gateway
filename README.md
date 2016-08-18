# Introduction to Swagger for CloudFormation and API Gateway

Sample project that shows how [AWS CloudFormation](https://aws.amazon.com/cloudformation/) can be
used to create an [AWS API Gateway](https://aws.amazon.com/api-gateway/) by using [Swagger](http://swagger.io/)
for configuring a RESTful API and map it to an [AWS Lambda](https://aws.amazon.com/lambda/) function.

Please read the [blog post](https://www.jayway.com/2016/09/18/introduction-swagger-cloudformation-api-gateway/) for details.

## CloudFormation Template

[cloudformation.template](cloudformation.template)


## Tools

In order to execute the scripts, you need to install the following tools:

- [AWS CLI](https://aws.amazon.com/cli/) (AWS Command Line Interface)
- [npm](https://www.npmjs.com/) (JavaScript package manager)


## Scripts

| Script                                                        | Description                |
| ------------------------------------------------------------- | -------------------------- |
| [create-stack.sh](scripts/create-stack.sh)                    | Creates the stack          |
| [integration-test.sh](scripts/integration-test.sh)            | Executes integration tests |
| [update-stack.sh](scripts/update-stack.sh)                    | Updates the stack          |
