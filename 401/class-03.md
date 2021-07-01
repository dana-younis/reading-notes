# Review, Research, and Discussion
1.Name 3 real world use cases where you’d want to change the request with custom middleware?
- User Authentication 
- offers a "middleman" so both systems don't have to communicate to one other directly, thus if one goes down, the other may still run.
- Middleware user-focused messaging

2.True or false: The route handler is middleware?
- By definition, they are not middleware features. On routing methods, such functions are just manager functions. If they are utilized.

3.In what ways can a middleware function end the process and send data to the browser?
- By not calling next(), or by not having next in its params - i.e. (req, res) instead of (req, res, next).

4.At what point in the request lifecycle can you “inject” middleware?
- Access to the request object, the answer object and the next function for the middleware. The request is applied when the server receives the request.

5.What can cause express to error with “Request headers sent twice, cannot start a second response”?
- This could happen if you are telling the script to respond twice

## Definitions
**Middleware**: Software that acts as a bridge between server and client. 
**Request Object**: the object a client delivers to a server for creation, reading, updating or deleting functions to be executed.
**Response Object**: the object the server returns to a client after the request object is received.
**Middleware application**: middleware linked to an express instance using application ()
**Routing Middleware**: Middleware that is bound to an instance of express.Router()
**Test Driven Development**: A development style wherein you write tests first, before writing code.
**Behavioral Testing**: An agile software development process, stemming from TDD, that is based on the use of user stories, which are written down in a dedicated document. BDD relates to how desired behavior should be specified.

## Preview
What three things did you hear before, and are now clearer?
- Road Methods
- Parameters of route (difference between params, query, body)
- Paths of the route (specifically how to handle :name or :id open ended paths)

What three things do you want to learn in the next lecture/demo?
- Hoisting - techniques of prototyping
- Reliable


What are you looking forward to doing or seeing how it works?
- I'm happy to learn more about what we are doing. I feel like every day I grow a little bit more conscious of what's going in my code and can write and debug things a little more. But I have a long way to go and I want representatives.


# ES6 Classes
Classes are a pattern for object creation. They encapsulate codes for data processing. Classes in JS are prototype-built but also have certain syntax and semántics not used with class-like ES5 semántics.


# Using Express Routing
Routing indicates how customer requests are answered by the application's endpoints (URIs).

Using Express App Object methods, routing is defined which matches HTTP methods; for example, GET requests and app.post are handled by. See app.METHOD for a complete list. You may also use App.all() for all HTTP and App.use() methods, to provide a callback function for the middleware.

These routing techniques describe the callback function called when the program gets an application to the given route (endpoint) and HTTP methods (often referred to as 'handler functions'). In other words, a request is "listened" for the route(s) and method(s provided, and when it finds a match, the callback function supplied is called.

# Express Routing
With the introduction of the Express 4.0 Router, we are afforded more flexibility than ever before in creating our routes. To summarize, we can:

- Use express.
Router() several times to define groupings of routes
- Apply the express.Router() to a part of our site using app.
use()
- Use route middleware to handle requests
- Use route middleware to verify arguments using .
param()\s- Use app.route() as a shortcut to the Router to define multiple requests on a route.