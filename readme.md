# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To start app use command

`
docker-compose up
`

It will automaticaly start backend, frontend and Postgres.

To check everything is ok, go to http://localhost:3000/api/ping for backend and http://localhost:3001/register for frontend.