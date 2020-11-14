# README

Test Application build by Rails, Postgreql, Travis CI under Docker Environemt.

* Ruby version
2.5.8

* Database creation
Postgreql version 11.9

* How to run the test suite

```
rails test
```

* Docker

```
docker-compose up
# or when you update Gemfile or Dockerfile etc
docker-compose up --build

# How to login docker-container
docker-compose exec web bash
```

* Deployment instructions