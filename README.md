# aws-lambda-scala-demo
Scala RESTful Microservice demo using AWS Lambda and AWS API Gateway

Original article [here](https://aws.amazon.com/blogs/compute/writing-aws-lambda-functions-in-scala/)

### Usage

`sbt compile assembly` then use the zip in _target\scala-2.11_
to create an AWS Lambda function from the AWS web UI.

Add a RESTful API to it using AWS API Gateway.

Request payload sample:

```json
{ "firstName": "Ketcho", "lastName": "Metcho" }
```
