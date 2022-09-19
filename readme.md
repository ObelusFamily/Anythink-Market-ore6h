# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

##Steps to install and run the repo on your local machine:
 1) Install the Docker from the given link below:
	Link : https://www.docker.com/products/docker-desktop/
    if done already ignore this step.
 
 2) Check if docker is running or not using
	docker -v    &
	docker-compose -v
    in your terminal

 3) Through your terminal go to your root directory where your Anythink file resides.
    and run 
	docker-compose up 
    in your terminal 

 It will take some time to download the container.
	
	