# AWS: Events

1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server.
> Amazon API Gateway and Express Gateway both have their strengths and weaknesses. Amazon API Gateway has a compelling case for massively scalable API gateways at a competitive price point. With Express Gateway, you are responsible for hosting and running your own API Gateway, which may be more or less expensive depending on your experience and the load on your API Gateway. In particular, you may need to manage the number of Express Gateway servers you’re running and configure a load balancer in front of your gateway servers if your API has sufficient load, which may be cumbersome and expensive.

2. List the AWS Database offerings and talk about the pros and cons of each
> Relational Database. Relational databases store data with predefined schemas and relationships between them. ...
Amazon Aurora. ...
Amazon Relational Database Service (RDS) ...
Amazon Redshift. ...
Key-value Database. ...
Amazon DynamoDB. ...
In-memory Database. ...
Amazon ElastiCache for Memcached.

3. What’s the difference between a FIFO and a standard queue?
> Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

4. How can the server be assured a message was properly received?
> Returns 200 status code.

Serverless API - Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers

Triggers - A mechanism that initiates an action when an event occurs such as reaching a certain time or date or upon receiving some type of input

Dynamo vs Mongo - Only available on AWS, Deploy anywhere.

Dynamoose vs Mongoose - Dynamoose is a modeling tool used for dynamo and mongoose is used for mongo.

