FROM ruby:2.5
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs
RUN mkdir -p /bikebike/backend
WORKDIR /bikebike/backend
COPY Gemfile /bikebike/backend/Gemfile
COPY Gemfile.lock /bikebike/backend/Gemfile.lock
RUN bundle install
COPY . /bikebike/backend
