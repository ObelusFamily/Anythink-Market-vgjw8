# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

In order to set up a local enviroment you need to install docker on your machine and register fro an docker account. 
You can check if docker is installed correctly by typing "docker -v" and "docker-compose -v" which should return a working version. 
After that go to the local repository directory and "docker-compose up" to buil a local enviroment. This process takes a bit. 
You can check if your local database is working by visiting "http://localhost:3000/api/ping" in your browser.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register.  
