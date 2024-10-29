# AWS lambda runtime update in Go applications

This is a sample repository with a simple AWS Lambda function written in Go.

The function is deployed using Serverless framework.

There is an `old` directory with the go1.x runtime, which is not supported by AWS Lambda any more.

There is a `new` directory with the set of changes required for the application to deploy to AWS
successfully.