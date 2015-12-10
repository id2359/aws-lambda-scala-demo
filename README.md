# aws-lambda-scala-demo
Scala RESTful Microservice demo using AWS Lambda and AWS API Gateway

Original article [here](https://aws.amazon.com/blogs/compute/writing-aws-lambda-functions-in-scala/)

### Usage

1. `sbt compile assembly` => a fat _.jar_ in _target\scala-2.11_
2. Create an AWS Lambda function from the AWS web UI; upload the _.jar_ above as zip source.
3. Add a RESTful API to it using AWS API Gateway.
4. Request payload sample:

```json
  { "firstName": "Ketcho", "lastName": "Metcho" }
```
