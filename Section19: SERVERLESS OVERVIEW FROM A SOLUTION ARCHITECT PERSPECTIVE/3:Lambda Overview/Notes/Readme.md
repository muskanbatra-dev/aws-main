# LAMBDA OVERVIEW

# WHY AWS LAMBDA

## Lets take an example we have amazon ec2 , as we know they are virtual servers in the cloud and we have to provision them, so we are limited by the RAM and CPU, CONTINOUSLY RUNNING

## Scalling means intervention to ADD/REMOVE servers

## virtual FUNCTIONS - no servers to manage!

## limited by time - short executions

## Run - on demand

## Scalling is automated

[![Slide 1](../Slides/Slide1.png)](../Slides/Slide1.png)

# BENEFITS OF AWS LAMBDA

## Easy Pricing

### Pay per request and compute time

### Free teir of 1,000,000 AWS Lambda requests and 400,000 GB's of compute time

## Integrated with whole AWS suite of services

## Integrated with many programming languages

## Easy monitoring through AWS Cloudwatch

## Easy to get more resources per functions(up to 10GB of RAM)

## Increasing RAM will also improve CPU and network

[![Slide 2](../Slides/Slide2.png)](../Slides/Slide2.png)

# AWS LAMBDA LANGUAGE SUPPORT

## Node.js(JavaScript)

## Python

## Java

## C# (.NET Core)/ Powershell

## Ruby

## Custom Runtime API(community supported , example RUST AND GOLANG)

## lambda Container Image

### The container image must implement the Lambda Runtime API

### ECS/Fargate is preferred for running arbitary Docker images

[![Slide 3](../Slides/Slide3.png)](../Slides/Slide3.png)

# AWS LAMBDA INTEGRATIONS

## API GATEAWAY

### Create a REST API and they will invoke our lambda functions

## KINESIS

### will be using lambdas to do some data transformations on the fly

## DYNAMODB

### will be used to create some triggers, so whenever something happens in our database a lambda function will be triggered

## S3

### a lambda function will be triggered anytime a file is created in S3

## CLOUDFRONT

### cloudfront is lambda at edge

## CLOUDWATCH EVENTS EVENTBRIDGE

### This is whenever things happen in our infrastructure on AWS and we want to be able to react to things

### For example, say we have a codepipeline state changes and we want to do some

## CLOUDWATCH LOGS

### cloudwatch logs to stream these logs whenever you want

## SNS

### SNS to react to notifications in your SNS topics

## SQS

### SQS to process messages from your SQS Queues

## COGNITO

### to react to whenever a user logs into your database
