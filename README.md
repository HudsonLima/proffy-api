# Proffy API

This is the API project that will response to requests from both [Web App](https://github.com/HudsonLima/proffy) and the mobile app.
It is built with Node.js and Typescript. It also uses SQLite as a the storage database.

Proffy aims to connect education professionals with students. You can register as a teacher or simply search for a professional available according to the subject you want to learn.


## :hammer: Setup

```bash

# Install the dependencies
yarn install

# Create the tables in the database
yarn knex:migrate

# Run the app
yarn start
```

**API Routing:**

List of teachers:  `GET: /classes`

Create a new teacher: `POST: /classes`

Number of connections established: `GET: /connections`

Post a new connection: `POST: /connections`


## :computer: Dev dependencies

- typescript
- express
- knex
- sqlite3
- cors

## [Future featues](https://www.notion.so/Vers-o-2-0-Proffy-eefca1b981694cd0a895613bc6235970)
- [ ] Add support to Swagger-UI
- [ ] Unit Tests
- [ ] Relax teacher query
- [ ] User authentication
- [ ] Password recovery
- [ ] Proffy's profile
- [ ] Add support to paging


