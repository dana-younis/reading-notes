# Status Codes Based On REST Methods


* In your own words, describe what each group of status code represents:
100’s = the request has been recieved from the client and waiting the server to comply .

200’s = success request , tells the client that the request has been accepted.


300’s = redirection , which means that the request that have been srnt to the server is invalid.


400’s = client error , invalid request.


500’s = server errors



* What is a status code 202?
The processing request was approved, however it did not finish the procedure.



* What is a status code 308?
Indicates that the requested resource is relocated to the URL of the headers of the location.


* What code would you use if an update didn’t return data to a client? 204 No Content 


* What code would you use if a resource used to exist but no longer does?
410


* What is the ‘Forbidden’ status code?
403 Forbidden client error reply code shows that the server understands the application but does not allow it.


* What is middleware?
Middleware is a program that delivers common services and applications other than what the operating system offers. Middleware is widely used for data administration, application services, messaging, authentication and API administration.


* What does app.use(express.json()) do?
 recognize the incoming Request Object as a JSON Object.


* What is the difference beween PUT and PATCH?
You must give a whole payload as a request when wanting to update a resource with the PUT request, however you must supply only the Parameters you would want to edit with the PATCH request. Related to the following: Suppose we have a resource containing a person's initial and last name.


* What is the difference between a status 200 and a status 201?
Successful! Successful. The status code of 200 is by far the most prevalent. It simply indicates that the application is received and understood and handled. A 201 status code shows a successful request and thereby creating a resource