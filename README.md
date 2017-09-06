# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Tutorial
[link](http://edgeguides.rubyonrails.org/getting_started.html)

# Doker guide
## Install
* /user/local/bin/docker-compose, copy last version from github
* sudo chmod a+=x /user/local/bin/docker-compose
## Use
* sudo docker-compose up
* (sudo docker-compose run web rails new . --force --database=postgresql)
* (sudo docker-compose build)
* sudo docker-compose run web rake db:create
* sudo docker-compose down
* docker ps to see docker container
