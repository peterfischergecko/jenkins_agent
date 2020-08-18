# Jenkins Agent
## Description
Customized Docker images intended to be used as build agents for Jenkins.

## How to build
docker build --no-cache -f dockerfile -t jenkins-agent:java8-node10-0.9.3 ./