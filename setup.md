# Setting Up Your Development Environment

## Prerequisites
* node/npm

## Installation
* Clone hana-ui and hana-api repositories
* Install the [Angular 2 CLI](https://github.com/angular/angular-cli)
* Install [Docker for Mac](https://www.docker.com/docker-mac) (if you are using a mac)
* Place environment files in proper location
  * aws.env, aws.env.encrypted, and var.env go in the root directory of hana-api
  * awsconfig.json goes in the src/mail directory

## Running the UI
* Run `npm install`
* Run `ng serve`

## Running the API
* Make sure Docker is running (open Docker for Mac)
* Run `docker-compose up`

* If you're getting errors, try running
```
# Delete all containers
docker rm $(docker ps -a -q)
# Delete all images
docker rmi $(docker images -q)
```
