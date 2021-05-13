# AWS: Events

## Review, Research, and Discussion

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

AWS gateway is equivalent to the express module. It handles server port listening, and HTTP traffic routing. It points requests to specific code on Lambda, which is equivalent to server js logic files in an express server.Responses from that logic pass back into the API gateway, which manages the HTTP response back to the client.

### List the AWS Database offerings and talk about the pros and cons of each

Redshift and RDS are SQL-like relational dbs, useful for highly complex data structures. 

DynamoDB is a key-value NOSQL-like db, useful for speed and simplicity.

Elasticache is an in-memory storage, useful for extremely fast data retreival

DocumentDB is mongoDB compatable document-based storage.

Other dbs include Neptune (graph-based), Keyspaces (wide column), Timestream (time series), and QLDB (ledger).

### What’s the difference between a FIFO and a standard queue?

A standard queue (on AWS) is capable of managing high throughput, but cannot guarantee first-in-first-out behaviour. FIFO queues cannot handle the same overall throughput, however it can guranatee each message will be delivered in specific FIFO order, and only once. This makes it useful for specific app logic tracking, or session management.

### How can the server be assured a message was properly received?

Upon receipt, the client can emit a confirmation message back to the server containing some info about what data was processed.

### Document the following Vocabulary Terms

### Term

**Serverless API** - an api who's logic lives entirely within the cloud (on AWS, using Lambda functions) such that the developer does not need to actually run and maintain a web server.

**Triggers** - Behaviours or actions that initiate lambda functions within AWS. Can be database actions, API activity, or many others.

**Dynamo vs Mongo** - Dynamo is AWS's cloud-based clone of a NOSQL database.

**Dynamoose vs Mongoose** - Dynamoose is the DynamoDB clone of Mongoose database interface for node.js.

### Preparation Materials

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
