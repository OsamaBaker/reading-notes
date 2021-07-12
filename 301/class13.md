# Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
100’s = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

200’s =These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

300’s =These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

400’s =hese are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

500’s =These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

2. What is a status code 202?
> Accepted 

3. What is a status code 308?
> Permanent Redirect

4. What code would you use if an update didn’t return data to a client?
> 204 No Content

5. What code would you use if a resource used to exist but no longer does?
> 308 Permanent Redirect

6. What is the ‘Forbidden’ status code?
> 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

# Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
> Because we might use it on a third party server, like Heroku, where it will not understand localhost.

2. What is middleware?
> Middleware is a (loosely defined) term for any software or service that enables the parts of a system to communicate and manage data.

3. What does app.use(express.json()) do?
> Lets the server accept json.

4. What does the /:id mean in a route?
> Gives access to whatever the client provides after the slash.

5. What is the difference beween PUT and PATCH?
> PUT updates all the information, PATCH updates what the user inputs in.

6. How do you make a defalut value in a schema?
> You pass in default into the keys.

7. What does a 500 error status code mean?
> There is an error on the server's side.

8. What is the difference between a status 200 and a status 201?
> Successfully created an something.