#Start with a base image containg java runtime
FROM openjdk:17-jdk-slim
#define the mainter if you have any not a mandatory field
MAINTAINER gaurav.com
#provide path where you can copy your jar file
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar
#using this command you java code will complie
ENTRYPOINT ["java","-jar","accounts-0.0.1-SNAPSHOT.jar"]