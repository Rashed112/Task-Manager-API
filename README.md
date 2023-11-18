# Task-Manager-API
This is a [Node.js](https://nodejs.org/en) project where 
  - [Express.js](https://expressjs.com/) was used to manage server and routes easily
  - [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/) were used to handle our data/database
  - [Postman API](https://www.postman.com/) was used for testing its expected functionality, security, performance, and reliability

## Getting Started
After cloning the repo, 
- first, install all the dependencies/devDependencies using the following command
  
  ```bash
  npm install
  ```
- then, to run the project use one of the following commands

  ```bash
  npm start
  # or
  nodemon app.js
  ```
- after that, open [http://localhost:3000](http://localhost:3000) with any of your favorite browsers to see the result.

## Speciality of the Project
  - This isn’t a typical to-do list app that stores everything in local storage, what’s fundamentally different is that we’re going to be responsible for setting up the API that communicates with the cloud database and persist the data to the cloud.
  - As for functionality, we’ve got the form and can enter a new task, and by submitting that we send off the **Post** request, and since we’re successful, we **Get** back all the tasks, and the newest task is added to the list. Then we can **Delete** the task. And if we want to **Update** that, we’ll see only the specific data on another page  about that one task. 

## Preview of the Project
  - In front-end we’ve got a form and a list and by submitting a task we can communicate with the backend, meaning by sending a request to the API, the user can **Create**, **Read**, **Update**, or **Delete** a task and to edit/update a task, it'll take us to another page.
  
    ![task-manager-1](https://github.com/Rashed112/Task-Manager-API/assets/44283694/be848b7a-8ba3-4ca2-b20d-fe1a3ada679a)
    ![task-manager-2](https://github.com/Rashed112/Task-Manager-API/assets/44283694/83a6824e-1cac-4667-827f-1c7a7585e18e)

## For Learning More About the Technologies
- [Node.js documentation](https://nodejs.org/en/docs)
- [Express.js documentation](https://expressjs.com/en/5x/api.html)
- [Mongoose documentation](https://mongoosejs.com/docs/)
- [Postman documentation](https://learning.postman.com/docs/introduction/overview/)
  
