# BobbleAI-DevOps-Assignment
## Link to my image -> https://hub.docker.com/repository/docker/mfzs/tomcatserver

This is my submission for Bobble AI's campus recruitment for DevOps Role at DIT University.

## Pre-requisites
  1. Install docker in your system by visiting https://docs.docker.com/get-docker/

## Steps to follow to run the project

### Assignment 1 -  Docker file (Tomcat Server)
  1. Build your docker file using  "docker build -t tomcatserver:v1 ." (dot(.) in case of present working directory otherwise give a full path where you want to build your image).
  2. Run your docker container "docker run -dit -p 9191:8080 --name myserver tomcatserver:v1".
  3. To attach docker "docker attach myserver".
  4. To run docker "docker start myserver".
  5. You can access your container using "localhost:9191   or  container_ip:9191   or 0.0.0.0:9191".

### Assignment 2 - Dockerhub 
  1. Goto the docker hub registry mfzs/tomcatserver or https://hub.docker.com/repository/docker/mfzs/tomcatserver.
  2. Download the image either using webui of docker or using cli "docker pull mfzs/tomcatserver:v1".
  3. Now use it according to your requirements.
