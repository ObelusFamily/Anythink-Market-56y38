# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker
2. Install docker-composer
3. Verify docker is installed with the following command: `docker -v`
3. Verify docker-compose is installed with the following command: `docker-compose -v`
4. Step into the root folder of the project
5. Start environment with the the following command: `docker-compose up`
6. Verify environment is up&running. Open in browser : http://localhost:3000/api/ping
