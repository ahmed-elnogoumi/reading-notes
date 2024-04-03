# Readings: Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.
    - Middleware is like a special service that modifies or directs letters (messages) between friends (computer programs) to ensure they're secure, fast, or translated correctly. It sits between the programs, handling tasks like security or communication standards, without being part of the actual conversation.
2. Express the most popular __ __ ____.
    - Node Web Framework
3. Express is “unopinionated.” What does that mean?
    - There aren't many restrictions on how to accomplish a goal.
4. What is a module and why is modularity useful to us as developers?
    - Modules in Node are reusable blocks of code that encapsulate implementation details and can be imported into other files, with modularity being crucial for managing complexity, facilitating code reuse, and improving maintainability in large applications.

## What is NPM?

1. What version of npm are you running on your machine?
    - 10.2.3
2. What command would you type to install a library/package called ‘jshint’ into your node project?
    - npm instlal jshint

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.
    - Tests allow you to check if the code written works properly.
2. What are three expected benefits of testing
    - Reduction in defect rates
    - Easier 'final phase' of development
3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
    - Forgetting to run tests
    - Writing tests that are too big
    - Team doesn't use tests.
    - Test for trivial code

## CI/CD

1. What are three benefits of Continuous Integration?
    - Continuous Integration catches bugs early, reduces integration problems, and enables faster development.
2. What is the difference between Continuous Delivery and Continuous Deployment?
    - Continuous Delivery automates the release process but requires manual approval, while Continuous Deployment automates deployment without manual intervention.
3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.
    - GitHub serves as a central hub where developers collaborate on code, which then gets automatically tested and prepared for release.