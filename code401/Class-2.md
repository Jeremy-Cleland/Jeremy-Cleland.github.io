# Readings: Express, NPM, TDD, CI/CD

## [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

- Q: Explain middleware, and answer as though I were a non-technical recruiter.

  - A: Middleware in the terms of Express.js are functions that execute during the processing of HTTP requests received by an Express application. Breaking this down, say you visited your favorite blog website and clicked a link for a product that took you to Amazon. For example, `<https://na.business-api.amazon.com/products/2020-08-26/products?productRegion=US&locale=en_US&keywords=laptop&facets=OFFERS&searchRefinements=search-alias%23electronics>` The HTTP request is then sent up and then passed along to middleware which could be looked as a mediator which could be tasked with looking for a cookie inside the request to decode the cookie so your favorite blog gets paid for referring you as a paying customer to purchase a product on Amazon. There are several types of middleware and this example is just one of the many types. Some other examples are loggers which log all of the requests made. Another one is Helmet which is a security middleware that protects Express.js apps by setting various HTTP headers.

- Q: Express the most popular ____ ____.

  - A: Node web framework

- Q: Express is “unopinionated.” What does that mean?

  - A: **Opinionated** frameworks are those with opinions about the "right way" to handle any particular task. They often support rapid development in a particular domain (solving problems of a particular type) because the right way to do anything is usually well-understood and well-documented.

  **Unopinionated** frameworks, by contrast, have far fewer restrictions on the best way to glue components together to achieve a goal, or even what components should be used. They make it easier for developers to use the most suitable tools to complete a particular task, albeit at the cost that you need to find those components yourself.^[1](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

- Q: What is a module and why is modularity useful to us as developers?

  - A: A module is a JavaScript library/file that you can import into other code using Node's require() function. Modules allow for easier testing and troubleshooting if errors arrise. 

   Express itself is a module, as are the middleware and database libraries that we use in our Express applications. ^[1](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

## [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

- Q: What version of npm are you running on your machine?

  - A: 9.4.0

- Q: What command would you type to install a library/package called ‘jshint’ into your node project?

  - A: `npm install --save-dev jshint`

## [What is TDD?](https://www.agilealliance.org/glossary/tdd/)

- Q: Explain why tests are important. Please explain as though I were your nontechnical elder.

  - A: Just like combat operations in Afghanistan you have to test. Testing enables the developer to better understand the code they are writing and ensure they have accounted for all possible bugs. 

- Q: What are three expected benefits of testing

  - A:
    - Significant reductions in defect rates.
  
    - The overhead of testing is more than offset with testing instead of not testing.
  
    - TDD leads to improved design qualities

- Q: Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

  - A:
    - Forgetting to run tests frequently
    - Writing too many tests at once

## [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

- Q: What are three benefits of Continuous Integration?

  - A:
    - Ensure everyone's changes interagrate
    - Catch Bugs
    - Reduce Merge Conflicts


- Q: What is the difference between Continuous Delivery and Continuous Deployment?

  - A:

    - CD is the practice of developing software in such a way that you could release it at any time. It also allows continuous delivery and lets you develop features with modular code. Continuous deployment is an extension of continous delivery. It's the process that allows you to actully deploy and experience little if any, downtime.

    - CI: is a workflow strategy that helps ensure that everyone's changes will integrate with the current version of the project.

- Q: Explain how GitHub fits into this process assuming the listener comes from a non-technical background
A: GitHub is like the clearning house. Developers make changes locally and push those changes to GitHub. GitHub uses webhooks to send messages to external systems. 

## Things I want to know more about
