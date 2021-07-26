# AWS: API, Dynamo and Lambda

## What are serverless functions?

Functions that run on the cloud and do some specific job for our main server based on events.

## If you were to create a system that emulated Lambda functions, how would you do it?

First I should write the serverless function then I need a platform that allow this service for example I can use AWS Lambda, then I need to add a trigger into another service that will invoke this function upon certain event.

## Describe how a CDN works

Content Delivery Network make a copy of the the content server and separate it to different locations around the world, when a user hit that server instead of going to that server it would send him to the closest server (CDN) to him, that process will make access to the content faster.

## Serverless Functions

Functions that run on the cloud and do some specific job for our main server based on events.

## Cloud Storage:

Is using some kind of database but in off-site location, on another server (cloud) that you access over the internet.

## CDN

Content Delivery Network, is a geographically distributed network of the server and their data centers.

Which 3 things had you heard about previously and now have better clarity on?
CDN, Serverless and cloud storage

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
CDN, Lambda

What are you most excited about trying to implement or see how it works?
AWS APIs and Dynamo

---

## Amazon API Gateway is

a managed service that enables developers to define the HTTP endpoints of a REST API or a WebSocket API and link those endpoints to the relevant backend business logic. It sits between your backend API and your consumers, and it can interact with other AWS services such as Amazon S3.

AWS Lambda allows you to run Lambda functions to produce HTTP API replies.

AWS SNS: When an HTTP API endpoint is visited, SNS notifications are published.

Amazon Cognito: offer HTTP API authentication and authorisation.

RESTful API and Websocket API are two API types.

- Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding
  backend business logic.
  It also handles authentication, access control, monitoring, and tracing of API requests.
  
- API Gateway sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends.
  It provides a set of tools that help you manage your API definitions and the mappings between endpoints and their respective backend services.
  It can also generate API references from your definitions and make them available to your users as API documentation.
  ### Benefits of Amazon API Gateway

- Map HTTP requests to specific functions in a Serverless application viaanAPI Gateway event.
- Map WebSocket events to Serverless functions.
- Use multiple microservices to serve the same top-level API.
- Save time with integrations: authentication, developer portal, CloudTrail, CloudWatch.

## DynamoDB:

AWS provides a No-SQL database. At any size, our key-value and document database offers speed in the single digit milliseconds.

DynamoDB is particularly well-suited to the following use cases:

Applications with high data volumes and stringent latency constraints.

AWS Lambda is used to run serverless applications.

Data sets having well-known, straightforward access patterns.

Dynamoose is a tool for modeling AWS DynamoDB.

Key Characteristics#

Type security

API at the highest level

Syntax that is simple to use

The ability to alter data before to storing or retrieving documents.

Data modeling must be strict (validation, required attributes, and more)

DynamoDB Transaction Support

Effective Conditional/Filter
Powerful Conditional/Filtering Support
Callback & Promise support



### It offers:

- reliable performance even as it scales;
- a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries;
- a small, simple API allowing for simple key-value access as well as more advanced query patterns.

### DynamoDB is a particularly good fit for the following use cases:

- Applications with large amounts of data and strict latency requirements.
- Serverless applications using AWS Lambda.
- Data sets with simple, known access patterns.

### Tables, Items, and Attributes

- DynamoDB's fundamental building pieces are tables, items, and attributes.

A table is a collection of data records. For example, you may have a Users table that stores information about your users, and an Orders database that stores information about your users' orders. A collection in MongoDB is analogous to a table in a relational database.

- An item in a table is a single data record. The specified primary key of the table uniquely identifies each item in the table. An entry in your Users table would be a specific User. A row in a relational database or a document in MongoDB are both examples of items.

- Attributes are pieces of data attached to a single item. This could be a simple Age attribute that stores the age of a user. An attribute is comparable to a column in a relational database or a field in MongoDB. DynamoDB does not require attributes on items except for attributes that make up your primary key.
