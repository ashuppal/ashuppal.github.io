#### AWS API Gateway Overview

What is Amazon API Gateway?
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. 
It also handles authentication, access control, monitoring, and tracing of API requests.

Why is Amazon API Gateway an important part of the Serverless ecosystem?
Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions.
Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: 
it enables a truly serverless architecture for web applications.

How does API Gateway integrate with other AWS services?
API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:

Invoking an AWS Lambda function.
Invoking another HTTP endpoint, with or without VPC Link.
Making an HTTP call against the API of any AWS service that provides an HTTP API.
Returning a mock response generated within API Gateway without calling out to other services.

#### AWS API Gateway

What are the some benefits of using Amazon API Gateway?
Efficient API development, Performance at any scale, Cost savings at scale, Easy monitoring etc.

What two API types might you choose from?
RESTful and Web Socket APIs

AWS DynamoDB Guide

What is DynamoDB?
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS).

Under what circumstances would you recommend DynamoDB over MongoDB?
DynamoDB is designed to be a high-performance, scalable database, and can handle millions of requests per second with low latency. 
This makes it a good choice for applications that require fast and responsive data access, especially those with unpredictable workloads. MongoDB is also scalable but may require more complex sharding configurations to achieve the same level of performance.


#### AWS DynamoDB

Explain to a non-technical friend how DynamoDB works.
DynamoDB is a type of database, which is like a digital filing cabinet where you can store information, which means it's really good at handling lots of information quickly and easily.

#### Dynamoose

What is Dynamoose?
Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose.

What are some key features of Dynamoose?
Type safety
High level API
Easy to use syntax
DynamoDB Single Table Design Support
Ability to transform data before saving or retrieving items
Strict data modeling (validation, required attributes, and more)
Support for DynamoDB Transactions
Powerful Conditional/Filtering Support
Callback & Promise support
AWS Multi-region support

