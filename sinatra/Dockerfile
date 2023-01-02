FROM ruby:2.7.6

COPY Gemfile .

RUN apt-get update
RUN apt-get install -y build-essential libmariadb-dev
RUN bundle install
