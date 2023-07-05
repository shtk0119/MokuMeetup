FROM ruby:3.2.2

RUN apt-get update -qq && apt-get install -y gcc g++ libc6-dev make

WORKDIR /app
COPY Gemfile /app/Gemfile

RUN bundle install
