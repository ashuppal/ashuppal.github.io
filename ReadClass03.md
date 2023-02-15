### Express REST API

#### Review: ES6 Classes

Classes are a template for creating objects.

Can a class declaration be hoisted?
No, class declaration can't be hoisted that means you cannot use a class before it is declared.

How would you describe a constructor and contextual “this” to a non-technical friend?
A constructor is a special method that is called when an object is created. A constructor is like a blueprint for the object.
In the context of a constructor, this refers to the object being created. 

#### Using Express Routing

Within Express, what does routing refer to?
Routing refers to how an application’s endpoints (URIs) respond to client requests.

What is the difference between a route path and a route method?
Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, 
string patterns, or regular expressions.The route method specifies the HTTP method or verb that the client is using to request the resource.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
The next parameter is used to call the next function or handler in the middleware stack. 
This can be useful when you have multiple middleware functions that need to be executed in order. If the next has been passed to your middleware as a 
parameter then the next function will call as soon as the first one is completed.

#### Express Routing

What is an Express Router?
The express. Router() function is used to create a new router object. 
This function is used when you want to create a new router object in your program to handle requests.

By what mean do we initialize express.Router() in an express server?
To use express.Router() you need to create an instance of the router object by calling express.Router(),apply routes to it, and then tell our application to use those routes.

What do we use route middleware for? (ref: expressjs.com)
Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle.
Middleware functions can intercept a request and either modify the request, modify the response, or pass control to the next middleware function in the stack. Middleware provides a way to separate the concerns of an application into smaller, reusable components.

#### Reflection
What are your learning goals after reading and reviewing the class README?
I want to practice more the CRUD Operations with REST and Express.
