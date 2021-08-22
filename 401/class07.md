# Bearer Authorization

1.
* Register your application to get a client_id and client_secret

* Ask the client if they want to sign in via a third party

* Make a request to a third-party API endpoint

* Redirect to a third party authentication endpoint

* Make a request to the access token endpoint

* Receive access token

* Receive authorization code

2. What can you do with an authorization code?
> An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space

3. What can you do with an access token?
> Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user's data.

4. What’s a benefit of using OAuth instead of your own basic authentication?
> It enables apps to obtain limited access (scopes) to a user's data without giving away a user's password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities.

Client ID - Is used to identify the application.

Client Secret - The client_secret is a secret known only to the application and the authorization server.

Authentication Endpoint - Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.

Access Token Endpoint - The token endpoint is where apps make a request to get an access token for a user.

API Endpoint - An API endpoint is a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program.

Authorization Code - The authorization code is a temporary code that the client will exchange for an access token.

Access Token - An access token is an object encapsulating the security identity of a process or thread. 