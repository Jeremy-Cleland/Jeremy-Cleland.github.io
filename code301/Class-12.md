# Class 12 Reading Notes | CRUD

## [Status Codes Based On REST Methods

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

- 100’s = Informational status codes that informs client about the header part of the request has been received and the server will try to comply with a transmission demand of the client
- 200’s = They tell the client that its request was accepted.
- 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore.
- 400s = They are all about invalid requests a client sent to a server.
- 500s = Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

## Discussion Questions

- Q: What is a status code 202?

  - A: This code tells the client that the request was valid, but its processing will finish sometime in the future.

- Q: What is a status code 308?

  - A: This tells the client to use another URL to access the resource and not use the current URL anymore.

- Q: What code would you use if an update didn’t return data to a client?

  - A: 204 No Content

- Q: What code would you use if a resource used to exist but no longer does?

  - A: 410 Gone

- Q: What is the ‘Forbidden’ status code?

  - A: 403 Forbidden

## [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

## Discussion Questions

- Q: Why do we need to pull our MongoDB database string out of our server and put it into our .env?

  - A: Because the server needs to be able to talk to MongoDB

- Q: What is middleware? Middleware gets executed after the server receives the request and before the controller actions send the response. Middleware has the access to the request object, responses object, and next, it can process the request before the server send a response.

- Q: What does app.use(express.json()) do?

  - A: parses incoming JSON requests and puts the parsed data in req.body.

- Q: What does the /:id mean in a route?

  - A: That's indicated that it is a parameter

- Q: What is the difference between PUT and PATCH?

  - A:
  - Put: PUT is a technique of altering resources when the client transmits data that revamps the whole resource.
    -Patch: PATCH is a technique for transforming the resources when the client transmits partial data that will be updated without changing the whole data.

- Q: How do you make a default value in a schema?

  - A: Set use the default keyword

- Q: What does a 500 error status code mean?

  - A: The server encountered an unexpected condition that prevented it from fulfilling the request

- Q: What is the difference between a status 200 and a status 201?

  - A:

  - 200: The request was received and understood and is being processed

  - 201: A 201 status code indicates that a request was successful and as a result, a resource has been created

### Things I want to know more about
