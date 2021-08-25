# docker-go-helloworld
This is a simple Hello world program in Golang with a Dockerfile to build image

To build the docker image run the following commands - 
- go mod init
- go build
- docker build --tag <tagname> .
  
To run the docker image in a container run the following command -   
- docker run <tagname>
