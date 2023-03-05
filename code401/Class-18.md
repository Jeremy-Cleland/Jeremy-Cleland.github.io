# Class 18 Reading Notes |  AWS: API, Dynamo and Lambda

## [AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

- Q: What is Amazon API Gateway?

  - A: Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

- Q: Why is Amazon API Gateway an important part of the Serverless ecosystem?

  - A: API Gateway links Serverless functions and API definitions in the Serverless ecosystem. API Gateway offers a true serverless architecture for web applications by directly triggering the execution of a Serverless function in response to an HTTP request. Using API Gateway and other AWS services, you can construct a fully functional customer-facing web application without managing a single server.

- Q: How does API Gateway integrate with other AWS services?

  - A: Many AWS services support integration with Amazon API Gateway, including:
    - AWS Lambda: run Lambda functions to generate HTTP API responses.
    - AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
    - Amazon Cognito: provide authentication and authorization for your HTTP APIs.

![Alt text](https://d1.awsstatic.com/serverless/New-API-GW-Diagram.c9fc9835d2a9aa00ef90d0ddc4c6402a2536de0d.png)

## [AWS API Gateway](https://aws.amazon.com/api-gateway/)

- Q: What are the some benefits of using Amazon API Gateway?

  - A:
    - Efficient API development
    - Performance at any scale
    - Cost savings at scale
    - Easy monitoring

- Q: What two API types might you choose from?

  - A: HTTP APIs and REST APIs

## [AWS DynamoDB Guide](<https://www.dynamodbguide.com/what-is-dynamo-db/>)

- Q: What is DynamoDB?

  - A: DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS).

- Q: Under what circumstances would you recommend DynamoDB over MongoDB?

  - A:
    - Reliable performance even as it scales

    - a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries

    - a small, simple API allowing for simple key-value access as well as more advanced query patterns.

## [AWS DynamoDB](https://aws.amazon.com/dynamodb/)

- Q: Explain to a non-technical friend how DynamoDB works.

  - A: Database service by Amazon

## [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

- Q: What is Dynamoose?

  - A: Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.

- Q: What are some key features of Dynamoose?

  - A:
    - Type safety
    - High level API
    - Easy to use syntax
    - DynamoDB Single Table Design Support
    - Ability to transform data before saving or retrieving items
    - Strict data modeling (validation, required attributes, and more)
    - Support for DynamoDB Transactions
    - Powerful Conditional/Filtering Support
    - Callback & Promise support
    - AWS Multi-region support

## Things I want to know more about

React Hooks