#### Review API Server Build

Explain the different between a query string parameter and a path parameter.

A query string parameter is a key value pair that is appended to the end of a URL. A path parameter is a key value pair that is appended to the end of a URL path.

What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com
v3
model name: stuff
id: things

http://our-site.com/v3/stuff/things


We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
when we say we've created a "dynamic" API with an "interface," we mean that we've built a really flexible translator that can work with many different programs and adapt to different situations.

Sure, I'd be happy to explain!

An API is like a set of instructions that different computer programs can use to communicate with each other. Think of it like a translator that helps two people who speak different languages understand each other.

Now, when we say we've created a "dynamic" API with an "interface," we mean that we've built a really flexible translator that can work with many different programs and adapt to different situations.

The "interface" is like a user-friendly front-end that allows people to interact with the API in a more intuitive way. It's like a menu at a restaurant that helps you order your food without having to know how to cook it yourself.



#### Review Auth Server Build

Describe how you would use middleware to implement basic and bearer auth.

In the case of basic auth, the middleware would check the request headers for a username and password. If the username and password are valid, the middleware would allow the request to continue to the server. If the username and password are invalid, the middleware would return an error message.

In the case of bearer auth, the middleware would check the request headers for a token. If the token is valid, the middleware would allow the request to continue to the server. If the token is invalid, the middleware would return an error message.


Describe the handshake necessary to implement OAuth.

The OAuth handshake involves the user clicking on a "Sign in with [service name]" button provided by the application, the application sending a request to the OAuth server, the OAuth server responding with a temporary code and a redirect URI, the application redirecting the user's browser to the OAuth server's authorization page, the user granting the application permission to access the requested scopes, and the OAuth server redirecting the user's browser back to the application's redirect URI with the temporary code.


Describe how Role Based Access Control works to a non-technical friend.


Role Based Access Control (RBAC) is a way to control access to resources in a system. It's like a security system that allows you to control who can access what parts of your house. In a system with RBAC, you can create roles that have different permissions. For example, you might have a role called "admin" that has permission to access all parts of the system, and a role called "user" that only has permission to access certain parts of the system.


