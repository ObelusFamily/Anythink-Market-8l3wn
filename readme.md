# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repo.
2. Run `docker-compose up`.
  - You'll want to make sure you have [Docker](https://docs.docker.com/get-docker/) installed!
3. Point your browser to http://localhost:3000/api/ping -- this is to ensure the backend is working as expected.
4. Point your browser to http://localhost:3001/register and try creating a user -- this is to ensure the frontend is working as expected.

That's all! Happy coding.
