# Docker-HelloWorld
Demo on How to Dockerize simple spring boot application

Steps to build docker image and run the image
1. Build docker image
   "mvn package docker:build"
2. list docker images to see latest build our image
   "docker images"  ex. springio/docker-helloworld
3. Run the docker image by below command
   "docker run -p 8090:8080 -t springio/docker-helloworld"
4. Get your docker machine IP using "docker-machine ip" ex."192.168.99.101"
5. Go to browser http://192.168.99.101:8090/
   you will see the result : "Hello Docker World"
