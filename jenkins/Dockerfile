FROM jenkins/jenkins:lts-jdk25

USER root

RUN apt-get update && \
    apt-get install -y docker.io curl && \
    apt-get clean