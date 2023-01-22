# Class 12 Reading Notes | CRUD

## [Status Codes Based On REST Methods

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

- 100’s = Informational status codes that informs client about the header part of the request has been received and the server will try to comply with a transmission demand of the client
- 200’s = They tell the client that its request was accepted.
- 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore.
- 400’s = They are all about invalid requests a client sent to a server.
- 500’s = Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

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

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

2. What is middleware?

3. What does app.use(express.json()) do?

4. What does the /:id mean in a route?

5. What is the difference between PUT and PATCH?

6. How do you make a default value in a schema?

7. 6What does a 500 error status code mean?

8. What is the difference between a status 200 and a status 201?

### Things I want to know more about
