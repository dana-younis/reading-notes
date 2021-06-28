# Express
## What is the difference between PUT and PATCH?
PUT utilizes a URI to replace the initial resource version, whereas PATCH gives instructions for modifying the resource the main distinction is
Can you call it deep vs shallow?

## Development tools or services to "mock" an API
JSON-Server
Js Mirage
Pretender
Postman

## APIDoc.js vs Swagger
APIDoc transforms comments from inline documentation into API documentation. When you edit routes, it is straightforward to update documentation side by side with the code. APIDoc can also be used to create a list of places to look for the comments in the source code.
You specify the place to look for these comments when you run the command:
> npx apidoc -i ./ -e node_modules -o ./docs 

This is to include the existing directory, but not 'node modules' and then './docs' output. The result is a static group of HTML pages you may access in your browser. You may be able to use this to, for example, GitHub pages.

/**
 * @api {get} /user/:id Request User information
 * @apiName GetUser
 * @apiGroup User
 *
 * @apiParam {Number} id Users unique ID.
 *
 * @apiSuccess {String} firstname Firstname of the User.
 * @apiSuccess {String} lastname  Lastname of the User.
 */

 ## Swagger utilizes the documentation in JSON format to use SwaggerUI
In contrast to APIdocs, Swagger creates the documentation by using a JSON file. The advantage is that the source code and documentation may be kept separate. It cleans your code and the documentation it creates looks honestly nice.
Compiling takes place using an online editor in real time as well.

Status codes for HTTP response
- Information answers (100-199)
- Responses to success (200-299)
- Retransfers (300-399)
- Errors in the client (400-499)
- Errors with the server (500-599)




# Document the vocabulary
A web server is the software and hardware that accepts applications for the distribution of web pages

## Express is a lean framework to create Node.js apps
Routing is the way requests and traffic are sent across a network
WRRC is the cycle of requests from web servers that supply web pages by clients.


1.What three things you had heard about before and are now clear?
Node.js is an executiontime that is unannounced outside the browser Express.
Refactoring is an important part of TDD

2.In a lecture, what 3 things do you want to learn?
What is a template? What is a template?
What are some libraries that may be used for middleware?
What is the mean of 100% coverage

3.What are you most excited to do or see how they work?
Middleware libraries, in particular the express library

## Node is an execution time for external usage that omits browser-related apis in favor of standard os apis.
## SOAP and ReST compare and compare: 
SOAP means simple access protocol for the purpose of objects; REST means transferring representational state.
It's a protocol for SOAP. With a specification, SOAP was designed. It comprises a WSDL file with the information needed to find out what the web service does in addition to the Web service address.
REST is an architectural paradigm in which web services may be considered exclusively as RESTful if it complies with Client Server Stateless Cacheable Layered System limitations
A single interface

SOAP employs service interfaces for customers, and REST utilizes Uniform service locators to access the component to its functionality.
# CD and CI
Ontino integration(CI) is the code and practice philosophy which encourages development teams to make minor changes and often check in repositories for version controls. Since most current apps need to create code on many platforms and tools, the team requires a system that can integrate and validate its modifications.

# Why we Use TDD:
"Code coverage" refers to the usage of TDD; although a high coverage doesn't ensure the adequate utilization of TDD, a deficiency of TDD mastery coverage below 80 per cent is likely to suggest.

In version management logs, test code should be verified in about equal quantities in every product code checked in.