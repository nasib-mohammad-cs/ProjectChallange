This direcotry contains the code and comand samples that i used for this task.

##steps to create the custom jenkins image out of jenkins with docker run support
1. a Dockerfile
FROM jenkins/jenkins:latest
USER root
RUN curl -sSL https://get.docker.com/ | sh
USER jenkins

=> docker build --tag jenkinsdock .
and then used this image in the compose file

