# Authentication
# Explain what a “Singleton” is (in Computer Science terms)
Singleton: is the process of limiting the class to a single instance and remembering the builder returns the same instance.

# Explain how the Singleton pattern can be used with Node modules, specifically with classes
We may use it to construct classes which we only need to instantiate once, for instance, simply to generate a single user by accident in the program
- Singletons may be created using:
1. Create regular class.
2. Create normal class.
3. Define a constructor's object settings as an object as you wish them to be (in accordance to your needs, with the keys and values you want).
4. Make the class instance the same as --> for the same class.
5. Write if the condition statement is (Class.instance == Class instance) {return Class.instance} --> indicating that the same class is returned every time you instance a new instance after the initial one.
6. You may also freeze the settings produced by Object.freeze to avoid user modifications (this.settings)
7. And by using Object.freeze, you may freeze the whole instance (this).
8. You can create methods to get the settings out of your object with a key as a parameter.

# If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
I will accomplish this work in the context of modularity in order to do everything that is organized on the server and to restrict certain actions in the app using Singleton.

# Which 3 things had you heard about previously and now have better clarity on?
Singleton pattern, Router middleware and CRUD apps.

# Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Dynamic Modules, Mocking the server or mock testing in general, what settings can we put in the singleton constructors.

# What are you most excited about trying to implement or see how it works?
Singleton Patterns and Dynamic Modules.

# Securing Passwords
Hash is the most important technique to secure passwords and is regarded to be quite safe for data or password integrity.

Bcrypt is a function of adaptive hash based on a cryptographic Blowfish cipher symmetric block cipher method, introducing a labor factor, which can decide how costly the hah function will be, also known as security factor.

# Basic Auth
Basic authentication is a mechanism for providing a user name and password to an HTTP agent (e.g. web browser) when requesting an access. A request contains the authorization header: Basic <credentials> in basic HTTP authentication. Encoded authentications. We use.set() to transmit the HTTP header request authentication.

Authentication: this is the process of checking if an individual, entity or website claims to be the person it is. Web applications are usually authenticated by sending a username or ID and one or more private information items which should only be available to a specific user.

# OWASP auth cheatsheet
https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html

# bcrypt docs
To install Bcrypt Package npm install bcrypt
https://www.npmjs.com/package/bcrypt



- Middleware functions are functions in the request-response cycle of the program which have access to the request-objective (req), the response-object (res), and the following middleware function. A variable named next usually indicates the next middleware function.

- The following can be done by middleware functions:
Run any code. Run any code. Modify the application and reply objects. Finish the cycle of query answers. Call the next stack middleware function 

- The following sorts of middleware may be used for an express application:
Middleware application level Middleware router level Middleware Error-Treatment Middleware built-in Middleware of the third party

- Dynamic Module Loading:
Loading dynamics: is the module import and export process dynamically rather than provide a static string; if the export and export for the module statements. Run and execute functions and variables of the module. Unload the memory module as well.

- Singleton Pattern:
When the class is reduced to one instance, and the constructor is remembered, the same instance returns.