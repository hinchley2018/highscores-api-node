# highscores-api-node
- Port my highscores api to nodejs

## Business Requirements
- build a highscores api to hold students' video game scores
- the data property
    - first-phase: should be a string,
    - car-mode: handle any json object a student sends
- 2 resources
    - highscores : (each high score has data for a given user id)
    - users: (has a username that responds to an id)
- a user can have many highscores

## Technical Requirements
- make the api documented in this [pdf](docs/highscores-api-documentation.pdf), here is swagger tutorial https://javascript.plainenglish.io/how-to-implement-and-use-swagger-in-nodejs-d0b95e765245
- use `swagger-jsdoc` `swagger-ui-express` packages to document endpoints in above pdf
- mongodb will be the database hosted in atlas
- Deploy the app to heroku following their documentation (free until heavy usage) 
- wire up CI/CD so every commit to `main` or `master` deploys it
