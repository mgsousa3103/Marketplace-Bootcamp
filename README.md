<h2 align="center">
Standard Marketplace API RESTFull
</h2>

<p align="center">This API works like a standard marketplace that provides user authentication, creating ads and sending email when purchasing a product</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/github/license/mgsousa3103/Marketplace-Bootcamp" alt="License MIT">
  </a>
</p>

## Features

These are some resources that were used in this project

- 💹 NodeJS
- 💹 Express
- 💹 JSON Web Token
- 📄 Mongoose

## Getting started

1. Clone this repo using `git clone https://github.com/mgsousa3103/Marketplace-Bootcamp.git`
2. Move yourself to the appropriate directory: `cd Marketplace-Bootcamp`

#### Getting started with backend

For this project you will need [Redis](https://redis.io/) and [MongoDB](https://www.mongodb.com/) on your machine. I used [Docker](https://www.docker.com/) to install them.

1. Run `yarn` to install dependencies
2. Access the `.env` file and change the settings. Look at the `.env.example` file if in doubt.
3. Run your MongoDB and Redis database
4. Run `yarn start` to start the application

#### Routes

| Route        | Type   | Result                                  |
| ------------ | ------ | --------------------------------------- |
| `/users`     | POST   | Creates an user                         |
| `/sessions`  | POST   | Creates a session with a JWT Token      |
| `/ads`       | GET    | Returns all ads created                 |
| `/ads/:id`   | GET    | Returns a specific ad based on ID       |
| `/ads`       | POST   | Creates an ad                           |
| `/ads/:id`   | PUT    | Updates an ad based on ID               |
| `/ads/:id`   | DELETE | Deletes an ad based on ID               |
| `/purchases` | POST   | Send an email with purchase requisition |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) page for details
