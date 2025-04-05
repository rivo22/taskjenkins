FROM jenkins/jenkins:alpine
USER root
#Install Docker CLI
RUN apk add -no-cache docker git
USER jenkins
