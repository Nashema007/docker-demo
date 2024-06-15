# Build Docker Image Demo

This is a demo to illustrate how to build a docker image that houses a simple Nodejs application based on the tutorial from https://www.youtube.com/watch?v=pg19Z8LL06w

# Run

To run application use the following commands:

* docker build -t `<image-name>`:`<image-tag>` `<dockerfile-location>`
* docker run --name `<app-name>` -d -p `<dest-port>`:`<src-port>` `<image-name>`:`<image-tag>`

# Requirements

* Docker
* Node
