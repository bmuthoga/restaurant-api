# Restaurant API

This is a simple API using Express and Mongoose (MongoDB ORM)

# Getting Started
## Prerequisites
Ensure you have the following installed locally:
- [Node](https://nodejs.org/en/)

## Installing
Clone this git repository:
```sh
$ git clone https://github.com/bmuthoga/restaurant-api.git
```
Navigate into the root of the cloned directory:
```sh
$ cd restaurant-api
```
Install all dependencies:
```sh
$ yarn
```

## Available Scripts

#### `yarn dev`

Runs your server in development mode.

#### `yarn build`

Builds your server for production environment.

#### `yarn start`

Runs your server in production mode.

#### `yarn lint`

Runs eslint for identifying and reporting on patterns in JavaScript.

## Use API locally
Once the server is running, you can now make requests to it using a client of your choice, such as `Postman`
  - ` GET /v1/restaurant` fetch all restaurants <br/><br/>
  - `POST /v1/restaurant/add` create a new restaurant <br/><br/>
  - `GET /v1/restaurant/:id` fetch restaurant by id
  - `PUT /v1/restaurant/:id` updates restaurant info by id
  - `DELETE /v1/restaurant/:id` deletes restaurant by id
