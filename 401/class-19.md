# AWS: Events


## Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
When using Express server, you connect and send HTTP requests to specific endpoints and connect them with handler functions on the same server, whereas when using AWS, you can separate the routing process and the function handler, where you send the HTTP request using AWS API Gateway and integrate them with Lambda functions as they will be triggered when a specific route is reached, and all of this process will be servlet-based (using AWS cloud as a server for your app).

## List the AWS Database offerings and talk about the pros and cons of each
AWS Dynamo --> is a No-SQL database that allows you to store and manage data. It also offers a package called Dynamoose that will let you connect to DynamoDB more simply.

AWS S3 --> Simple Storage service, allow you to store specific issues or maybe back-up your data for later time. 

## What’s the difference between a FIFO and a standard queue?
FIFO --> is a data flow method that stands for First In, First Out.

Queue --> is a data structure (data storage technique) that uses a FIFO data flow methodology and allows you to add methods like as peek, isEmpty, enqueue, and dequeue.


### How can the server be assured a message was properly received?
By adding a Messaging Queue to the server, all requests will be added to this Queue before being processed, and then adding an event to this Queue that whenever a client received a message delete from the Queue (also add the trigger on the client side), we can ensure that the data is not lost and that all clients received it properly.




## Serverless API
An API server that deal with HTTP request and responses but on another server (not locally in our app).

## Triggers
An event triggers that will invoke the function handler in the event listener.

## Dynamo vs Mongo
They are booth No-SQL database and both of them have a package that will help us in connecting to the DB and manipulating the data (Mangoose and Dynamoose).

## Dynamoose vs Mongoose
Packages to connect to MongoDB and DynamoDB and manipulate the data more easily.


Which 3 things had you heard about previously and now have better clarity on?
DunamoDB, Serverless API and FIFO

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
SNS and SQS

What are you most excited about trying to implement or see how it works?
AWS SNS and AWS SQS

----------------------------------------------------------------------------------------------------------------------------------

## AWS SQS 
A service from Amazon (Simple Queue Service) provides two Queue services, the first of which is Standard Queue, which is expandable based on use. Second, a FIFO queue will ensure that messages are sent in the correct sequence, and it will employ messaging groups to facilitate scalability.





## AWS SNS
A Pub/Sub message (which sends messages from a publisher to a certain topic, then the sub receives a copy of all distinct messages) might include subscribers that are other AWS services like Lambda functions, SQS, or API. Async




SQS : Pull Mechanism – SQS messages are polled by consumers.
SNS : Push Mechanism – SNS sends messages to users.

SQS: Messages are retained for a certain period of time if no consumer is present. The retention duration ranges from one minute to fourteen days. The default setting is four days.
SNS: There is no perseverance. The message is delivered to whatever consumer is present at the moment of message arrival, and the message is destroyed. If there are no customers accessible, the message is lost.
Message delivery is guaranteed in SQS but not in SNS.

AWS is used to create microservices.

Message Streams (AWS Kinesis) are distinct from message queues in that messages in streams are permanent (will not be removed). And we utilize it when we want to analyze the sequence of messages.

SQS : Pull Mechanism — Consumers poll messages from SQS.
SNS : Push Mechanism — SNS pushes messages to consumers.



**Consumer Type**

SQS : All the consumers are supposed to be identical and hence process the messages in exact same way.
SNS : All the consumers are (supposed to be) processing the messages in different ways.