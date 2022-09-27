# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

**[27/09/2022 @midix]:** After cloning the project, you need to intall [docker](https://docs.docker.com/get-docker/). Then, verify if the docker is ready to run by runing the commands : 
```
docker -v
docker-compose -v
```
For start the docker container you will need to run :
``` 
docker-compose up
``` 
To check if all the containers are runing correctly go to http://localhost:3000/api/ping and add an account on http://localhost:3001/register. Then you good to go.