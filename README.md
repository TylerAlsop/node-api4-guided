# Node API 4 Guided Project

Guided project for **Node API 4** module.

In this project we will learn how to deploy a Web API to `heroku`.

## Prerequisites

- Sign up for a free account on [Heroku](https://www.heroku.com/).

## Instructions

Please fork this repository and follow along **using your fork** as the instructor deploys the API to `heroku`.


In the root folder:
npm install --save-dev cross-env

In package.json .scripts.watch "cross-env COHORT=webpt12 nodemon index.js"

In welcome router: 
Welcome message: `Welcome ${process.env.COHORT}`

In the root folder:
npm install dotenv --save-dev

