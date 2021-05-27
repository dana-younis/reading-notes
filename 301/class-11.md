#  Authentication

## What is OAuth

* 1.What is OAuth?
Auth does not disclose password information but uses tokens for authorizing users and service providers to establish their identity. OAuth is an authentication technique that enables you to accept an application which interacts without password on your behalf.


* 2.Give an example of what using OAuth would look like.

When we wish to connect on to a new account with a different account exactly like we check on on GitHub to Netlify.


* 3.How does OAuth work? What are the steps that it takes to authenticate the user?

The first website, which provides the confirmed user identity, links the second website on behalf of a user using OAuth.
The second website produces a single token and a unique secret for all parties engaged in the transaction.
This token and secret is provided on the initial site to the client software of the beginning user.

The customer software offers its authorization provider the token and secret (which may or may not be the second site).

If the authorization provider is not already authenticated, the client might be requested to authenticate. The customer is requested to authorise the authorisation transaction to the second website after authentication.
A certain sort of transaction on the first website is approved by the user (or its program quietly authorizes).
A token is issued for the user (note that it is not a request token anymore).
The user provides the first website with the allowed access token.

As evidence of an authentication for the user, the first website provides the access token to the second website.

On behalf of the user the second website provides access to your site.
The user sees a transaction successfully completed.
The OAuth system is not the first to operate in this fashion on behalf of the end user. Actually, many authentication systems function similarly, especially Kerberos. OAuth's ability to work the whole internet and its broad acceptance is exceptional. Adoption rates were successful when prior efforts failed (for various reasons).

* 4.What is OpenID?
OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords


## Authorization and Authentication flows

* What is the difference between authorization and authentication?
Simply said, it's like allowing someone to do something or anything. For example, the verification process and confirmation of employee ID and passwords in an organisation, which employee has access to which floor is termed authorisation, is referred to as authentication.

* 2.What is Authorization Code Flow?

The Flow+PKCE Authorisation Code is an OpenId Connect flow created primarily for authentication to native or mobile users.

* 3.What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Authorizations are issued to the application itself in the customer credentials flow by an admin. When an app displays a resource token, the resource causes the app to take an action since the user invoice does not exist.

* What is Implicit Flow with Form Post?
OAuth 2.0 provides an Implicit Flow to Public Clients or apps that cannot safely keep Client Secrets as an alternative to the authorization codes flow. Although this is not regarded as a recommended practice for obtaining Access Tokens, it does allow a shortened workflow if the application requires just an ID token for user authentication if it is utilized in the Form Post mode.



* 5.What is Client Credentials Flow?
Authorizations are issued to the application itself in the customer credentials flow by an admin. The resource compels the app itself to carry out an action when the token is displayed to a resource since no user participates in the authorization process.



* 6.What is Device Authorization Flow?


* What is Resource Owner Password Flow?
The flow of resource owners passwords allows the username and password of a user to be exchanged for an access token and a refresh token. The main distinction is that the program may access the user's password. This needs the user to have significant confidence in the program.