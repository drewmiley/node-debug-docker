# node-debug-docker

Simple example of debugging node in a docker containers

## To run

1. docker build -t node-debug-docker .
1. docker run -p 3001:3000 -p 9229:9229 -d node-debug-docker
1. Find node dev tools at chrome://inspect (files cannot be added as they are in docker container - use console.log)