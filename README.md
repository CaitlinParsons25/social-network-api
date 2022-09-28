# Social Network API

## This social network API uses a NoSQL database so that a site can handle large amounts of unstructured data.

- [Usage](#usage)
- [Technologies used](#technologies-used)
- [Installation](#installation)

## Usage
This project consists of back end API routes, so make sure you have Insomnia (or your preferred API route-testing application of choice) installed.

## Technologies used
- JavaScript
- Express.js
- Node.js
- MondgoDB
- Mongoose

## Installation
In an indepedent terminal, start your MongoDB server according to your machine. If you have not yet installed MongoDB or need a refresher on how to start it, visit [MongoDB's website](https://www.mongodb.com/docs/manual/administration/install-community/).<br>
After downloading the code and after your MongoDB is up and running, in an integrated terminal, run the following commands:<br>
`npm i`<br>
`npm install`<br>
This will ensure you have the correct node dependencies installed. Then, to connect to the server so you can test the routes, run `npm start` and open your route-testing application. The routes will be tested at `http://localhost:3001/api/`, with the rest of the url dependent upon which route you are testing.
