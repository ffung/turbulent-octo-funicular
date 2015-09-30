# Advanced docker-compose demo

## Setup

### Add labels to the Docker daemons to be able to target them
Modify the Docker options to add the labels
DOCKER_OPTS="--label environment=staging"

## Run docker-compose
docker-compose -f [staging|production].yml up -d


## Check
docker-compose -f [staging|production].yml ps
