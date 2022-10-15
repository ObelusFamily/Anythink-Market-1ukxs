# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone repo into local machine
2. cd into repo in the terminal
3. Download docker to local machine
4. run `docker-compose up`
5. test backend by visiting `http://localhost:3000/api/ping`
6. test frontend and backend connection by creating new user `http://localhost:3001/register`
