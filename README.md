# todo-devops
## Local Environment setup
- Clone the repository using git clone.
- Run npm install on server and todolist directory to install all the dependencies.
- Move to ./server directory and type node index.js in terminal this will run the express server of the application which will listen on port 3000
- After starting up the server open up a new terminal and move to ./todolist directory of the project and type npm run dev in the terminal which will start the react application on port 3000.
- As mongodb-server setup is dependent on ./docker-compose.yml file which currently is under development due to the bug so it will not start with docker compose up, only front-end service will be function with server but will not functional completely as it doesnot have a database attached to it. If you wish to add database you can do so locally by changing the mongo-url in your local repository with your mongodb url which should work fine after that.
- Docker compose up will be available after the bug fixing.

### ***Thank You!***
