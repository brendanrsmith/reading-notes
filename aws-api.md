# AWS: API, Dynamo and Lambda

## Review, Research, and Discussion

### What are serverless functions?

Serverless functions are self-contained programs which are able to be hosted and run entirely on a cloud server. While they do technically use a 'server', they do not require a developer to administrate one in the traditional sense. Amazon Lambda is an example.

### If you were to create a system that emulated Lambda functions, how would you do it?

I would create a server which imported the Lambda function as a module, and use an event handler to listen for a call to that function from the client.

### Describe how a CDN works

A CDN hosts a given resource on many different servers at many locations. This way, if a large number of clients in a broad range of locations all want to acccess that resource simultaneously, they only have to hit one of many nearby servers, rather than all hitting the same server. This increases overall bandwidth as well as reducing latency.

## Terms

**Serverless Functions** - Conventionally, serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies [src](https://www.pubnub.com/blog/what-is-a-serverless-function/)

**Cloud Storage** - Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. [aws](https://aws.amazon.com/what-is-cloud-storage/)

**CDN** - a geographically distributed network of proxy servers and their data centers. The goal is to provide high availability and performance by distributing the service spatially relative to end users. [src](https://en.wikipedia.org/wiki/Content_delivery_network)

## Preparation Materials

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

[AWS API Gateway]
[AWS DynamoDB Guide]
[AWS DynamoDB]
[Dynamoose]
