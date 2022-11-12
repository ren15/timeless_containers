# timeless_containers

## Goal

Don't pay the cloud provider for "provisioned" containers, instead it needs to scale to 0.


## Existing solutions 

Close

- GCP cloud run
- AWS App runner 
- AWS Lambda 

Open

- OpenFaaS
- Knative


## Requirements 

- Interface for traditonall apps/languages that are hard to add a HTTP request interface.
- Container based, accept Dockerfile for building images and deployment

## TODO:

- Convert any app that listens to `localhost:$PORT` to AWS Lambda and handle request by URL.


