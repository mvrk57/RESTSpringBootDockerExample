FROM ubuntu:latest

MAINTAINER Manuel Mueller "manuel.mm.mueller@icloud.com"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin/

COPY testapp.jar .

CMD  ["java","-jar","testapp.jar"]