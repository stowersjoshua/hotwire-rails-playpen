# ChatterBox - A Hotwire Experiment

This project loosely follows [the Hotwire introduction demo](https://www.youtube.com/watch?v=eKY-QES1XQQ) to build a simple chat application. 

The repo is a personal playground for learning about Hotwire, Turbo, Stimulus, and Strada. 
It uses Rails 6.1.0. Ruby 3.0.0, and Bootstrap 5.

## Setup

There is no Procfile or anything fancy like that.

```
rvm use 3.0.0
bundle install
rails db:create db:migrate
redis-server
./bin/webpack-dev-server
bundle exec rails server
```
