# Bike!Bike!

## Tech stack

- [Ruby](https://www.ruby-lang.org/en/) 2.5.3
- [Rails](https://rubyonrails.org/) 5.2.1
- [React.js](https://reactjs.org/) 16.5.0
- [TypeScript](https://www.typescriptlang.org/) 3.0.3
- [Docker](https://docs.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)

## Getting started

### Pull down the repo

```shell
$ git clone https://github.com/BikeCollectives/bikebike.git
$ cd bikebike
```

### Set up the docker containers

```shell
$ docker-compose run bikebike yarn
$ docker-compose run backend rake db:create
$ docker-compose run backend rake db:schema:load
```

### Start the server

```shell
$ docker-compose up --build
```

### Visit the site

You should be able to access your dev instance at [http://localhost:3000](http://localhost:3000)
