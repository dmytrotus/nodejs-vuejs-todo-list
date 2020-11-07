> An app to demonstrate CRUD with a REST API 

## Tech Used

Client/Frontend:
* Generated Vue project using [Vue CLI v4](https://cli.vuejs.org/)
* [VueJs (Vuex + Vue Router)](https://vuejs.org/)
* [Axios](https://github.com/axios/axios)
* [Buefy](https://github.com/buefy/buefy)

Server/Backend:
* [NodeJs](https://nodejs.org/en/)
* DB - [MariaDB](https://mariadb.com/kb/en/getting-started-with-the-nodejs-connector/)
* REST API - [Express](https://expressjs.com/)
* ORM - [Sequelize v6](https://sequelize.org/)

# Installation

### Pre-Requisites
> Below must be installed on your executing machine

* [MariaDB Server 10.5.5](https://mariadb.org/download/)
* Nodemon `npm i -g nodemon
---
## Setup


## Client

1. Change directory to `client`

    ```bash
    $ cd .\client\
    ```

2. Run npm install

    ```bash
    $ npm install
    ```

3. Run the client
    ```bash
    $ npm run serve
    ```

## Server


1. Change directory to `server`

    ```bash
    $ cd .\server\
    ```

2. Run npm install

    ```bash
    $ npm install
    ```

3. Create .env file in `/server` with the following (change as appropriate):

    ```env
    DB_NAME=my-vue-db-name
    DB_USER=root
    DB_PASSWORD=password
    ```

4. Run the server:

     ```bash
    $ npm start
    ```
