# Class 34 Reading Notes | API Integration

## [Review API Server Build]()

- Q: Explain the different between a query string parameter and a path parameter. Path parameters are part of the endpoint and are required. For example, `/users/{id}`, `{id}` is the path parameter of the endpoint `/users`- it is pointing to a specific user's record. The users inputs the query parameters can be defined as the optional key-value pairs that appear after the question mark in the URL.

  - A: Path parameters are request parameters attached to a URL that point to a specific REST API resource

- Q: What would our API URL with a path id parameter be given the following information:
  1. Domain: <http://our-site.com>
  1. v3
  1. model name: stuff
  1. id: things

  - A: <http://our-site.com/api/v3/stuff/things>

- Q: We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
  
  - A: Think of an interface as a way for humans to interact with a machine. In this case, the machine is the API we  created. The interface is like a menu or a dashboard that allows you to input information and get back results. It's designed to make it easy for you to use the API without needing to know any technical details. You can think of it like ordering food at a restaurant where you tell the waiter what you want, and they bring it back to you. Similarly, with an API interface, you input the data you want to use or the function you want to perform, and the API returns the results to you. The interface is user-friendly, intuitive, and designed to make it easy for anyone to use the API, even if they have no technical expertise.


## [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

- Q: Describe how you would use middleware to implement basic and bearer auth.

  - A:

  1. Basic Authentication: This is a simple authentication method that encrypts the username and password in base64 format and sends it over the network. To use middleware to implement basic authentication, follow these steps:

- Create a middleware function that checks if the authorization header is present in the request.
- If the header is present, decode the base64-encoded string and extract the username and password.
- Validate the username and password against the database or any other authentication service.
- If the credentials are valid, allow the request to pass through to the next middleware function or the server.
- If the credentials are invalid, return a 401 unauthorized error.

2.Bearer Authentication: This is a more advanced authentication method that uses a token instead of a username and password. To use middleware to implement bearer authentication, follow these steps:

- Create a middleware function that checks if the authorization header is present in the request.
- If the header is present, extract the token from the authorization header.
- Validate the token against the database or any other authentication service.
- If the token is valid, allow the request to pass through to the

- Q: Describe the handshake necessary to implement OAuth.

  - A:

  Auth uses a series of handshakes to authenticate and authorize access to protected resources. The steps involved in the handshake process are as follows:

1. The user requests access to a protected resource from a third-party application.
2. The third-party application generates a request token and secret and redirects the user to the authorization server.
3. The user authenticates with the authorization server and grants permission for the third-party application to access their protected resources.
4. The authorization server generates an access token and secret and sends them to the third-party application.
5. The third-party application uses the access token and secret to access the user's protected resources.

In summary, the handshake involves the user, the third-party application, and the authorization server exchanging tokens and secrets to authenticate and authorize access to protected resources.

- Q: Describe how Role-Based Access Control works to a non-technical friend.

  - A:

  Role Based Access Control (RBAC) is like a bouncer at a club who checks your ID and decides if you're allowed in or not. In RBAC, different people are given different roles, like a manager or an employee. Each role has different levels of access to different parts of a system, like a computer program or a database. So, just like the bouncer at the club, RBAC checks who you are and what role you have, and then decides what parts of the system you're allowed to access. This helps keep the system secure and ensures that people only have access to the parts they need to do their jobs.


## Bookmark and Review



## Things I want to know more about
