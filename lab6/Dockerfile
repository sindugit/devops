FROM ruby:latest

RUN bundle config --global frozen -1
RUN apt-get update -y
RUN apt-get install -y ruby-sinatra

COPY helloworld.rb helloworld.rb
EXPOSE 3000
CMD  ["ruby"," helloworld.rb"]
