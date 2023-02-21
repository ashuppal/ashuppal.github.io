#### Intro to JWT

What is a JSON Web Token (JWT)?
JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information 
between parties as a JSON object. 

When should we use JSON Web Tokens?
JSON Web Tokens are useful for Authorization, Information Exchange.

Claims are expected in which structural component of a JWT?
Claims are expected to be found in the payload component of a JWT.


#### Are JWTs Secure?

If I get a JWT and I can decode the payload, how can we call that secure?
Even if you are able to decode the contents of a JWT, you still cannot modify the token without knowing the secret key used to sign it.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
When sending a JWT, both the sender and receiver must know the same shared secret key.

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
When sending and receiving JWT, the sender and receiver have a secret piece of information that is known only to them. 
This shared secret is used to create the digital signature that ensures the authenticity of the token.

#### Why use JWT?

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
JWTs are compact because they are smaller in size compared to other token formats.
JWTs are self-contained because they include all the necessary information within the token itself. 

What are the three components (the structure) of a JWT signature?
The three components (the structure) of a JWT signature are:
Header, payload and signature.


## Things I want to know more about
When to use Basic or Bearer Authentication

