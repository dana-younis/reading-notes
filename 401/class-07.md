# Bearer Authorization 


OAuth is a (delegated authorization) framework for REST/APIs. like when using facebook and instagram.

Write the following steps in the correct order:

 1. Ask the client if they want to sign in via a third party.
 2. Make a request to a third-party API endpoint.
 3. Register your application to get a client_id and client_secret.
 4. Redirect to a third party authentication endpoint.
 5. Receive authorization code.
 6. Make a request to the access token endpoint.
 7. Receive access token.



What can you do with an authorization code?
It allows the user to get access for Tokens.

What can you do with an access token?
It allows apps to request an API on behalf of the user, it allows the user to access the data and it has to be securely sent and saved.

What’s a benefit of using OAuth instead of your own basic authentication?
- allows applications to access user data in a limited manner.
- No password to offer.
- It enables online, desktop and mobile authorizations.
- More confidential. (Tokens complicated)


The customer ID ---> for applications is easy. (Hex string of 32 characters)

Client Secret –-> it is a secret between your app and the permission server; only qualified users can be granted tokens.



Authentication Endpoint --> This is a route or technique for the identification or authentication of external devices for service connectivity.



Token Endpoint Access Token ---> is the location in which applications request access tokens.



Endpoint — -> API is the point and location for an application interface, an API for sending and receiving web application or web server requests (communicate between apps)



Authorization Code ---> provides the user with a temporary token code. The authorisation server is acquired from it.



Access Token ---> is like a password which specifies the permission for users to access information or data relevant to the (scope) of the access or enables applications to access APIs.



Which 3 things had you heard about previously and now have better clarity on?
Tokens, OAuth, client secret.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Authorization code, full cycle of accessing tokens, access token and authorization endpoints.

What are you most excited about trying to implement or see how it works?
how to generate access tokens.


JSON Web Token What is it?
JSON Web Token (JWT) is a compactly autonomous open-ended standard (RFC 7519) designed to secure information transmission as a JSON Object between parties. You can verify and trust these informations since they are signed digitally. The JWTs may be signed with a secret or public/private key pair (using the HMAC technique) utilizing RSA or ECDSA.


JWTs have three sections, divided into points --> header.payload.signature `xxxxx.yyyyy.zzzzz`


You can sign, encrypt or both of JWTs.