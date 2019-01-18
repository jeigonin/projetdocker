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


Run this commands to have the great configuration on POSTGRE : 


docker-compose exec db psql -h localhost -U postgres -c "CREATE USER root WITH PASSWORD 'root';"


docker-compose exec db psql -h localhost -U postgres -c "CREATE  database project;"

