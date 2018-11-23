# Bike!Bike!

## Tech stack

**Here is an example application with the following modern web technology stacks. With this boilerplate, you can easily start to build your own app.**

- [Ruby](https://www.ruby-lang.org/en/) 2.5.3
- [Rails](https://rubyonrails.org/) 5.2.1
- [React.js](https://reactjs.org/) 16.5.0
- [TypeScript](https://www.typescriptlang.org/) 3.0.3
- [Docker](https://docs.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)

## Getting started

```shell
$ git clone https://github.com/ohbarye/rails-react-typescript-docker-example.git && cd rails-react-typescript-docker-example

# Setup
$ docker-compose run bikebike yarn
$ docker-compose run backend rake db:create
$ docker-compose run backend rake db:schema:load

# Start
$ docker-compose up --build
```

Now you should be able to access your dev instance at [http://localhost:3000](http://localhost:3000)
