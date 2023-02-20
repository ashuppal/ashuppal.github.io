#### Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.

Hashing is a way of turning your password into a differen letters and numbers that are very difficult to unscramble. 
It is like a secret code that only the website can read. Website uses special mathematical formula to save your password.

What is Bcrypt?
Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces 
a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

Why might you use something like Bcrypt?
The main reason for using bcrypt is to protect users' passwords in case of a data breach or other security incident.

#### Basic Auth

What is Basic Authentication?
Basic authentication is a simple authentication scheme built into the HTTP protocol. 
The client sends HTTP requests with the Authorization header that contains the word Basic word followed by a space 
and a base64-encoded string username:password .

What properties are necessary in the header of a Basic Auth request?
Authorization header contains the Basic word followed by a space and a base64-encoded username:password string.

How are username:password in Basic Auth encoded?
Basic Authentication sends a Base64 encoded string that contains a user name and password for the client via HTTP headers.

#### OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter.
Authentication is the process of verifying the identity of a user that is trying to access a system or resource.
The authentication process is usually initiated by the user attempting to log in or access a protected resource, such as a website or application.

How should your error messaging respond (both HTTP and HTML)? Why?
HTTP errors are errors that are generated by the server in response to a client request. These errors are 404 Not Found or 500 Internal Server Error. 
HTML errors are errors that are generated by the client-side HTML, CSS, and JavaScript code. These errors are typically displayed to the user as a message on the 
webpage or within the application. 

## Things I want to know more about: Hashing