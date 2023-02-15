# Class 3 Reading Notes | Express REST API

## [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

- Q: Classes are a template for creating ____.

  - A: objects

- Q: Can a class declaration be hoisted?

  - A: No

- Q: How would you describe a constructor and contextual “this” to a non-technical friend?

  - A: In JavaScript, there are these things called Objects which can contain a variety of things. A recipe contains ingredients, and steps to follow to make that given reciepe. The recipe is the constructor and the meal is the object, and all of the ingredients are what is stored inside the object. When the dish is created you can refer to the dish with a keyword this, which allows us to reference the object (dish).

## [Using Express Routing](https://expressjs.com/en/guide/routing.html)

- Q: Within Express, what does routing refer to?

  - A: Routing refers to how an application’s endpoints (URIs) respond to client requests.

- Q: What is the difference between a route path and a route method?

  - A: The route method is the route derived from one of the HTTP Methods. The Route path defines the endpoint.

- Q: When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

  - A: In fact, the routing methods can have more than one callback function as arguments. With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback. The only exception is that these callbacks might invoke next('route') to bypass the remaining route callbacks. ^[1](https://expressjs.com/en/guide/routing.html)

## [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)

- Q: What is an Express Router?

  - A: Router is like a mini-Express application.

- Q: By what mean do we initialize express.Router() in an express server?

  - A: We will call an instance of the express.Router() we are then able to add routes. 


- Q: What do we use route middleware for?

  - A: Checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we provide the information to the user. 

## Things I want to know more about

Hooks