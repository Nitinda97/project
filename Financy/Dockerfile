FROM openjdk:11-jre-slim-buster
MAINTAINER nitin <nitin@gmail.com>
VOLUME /tmp
ARG JAR_FILE=target/financy-1.0.10-SNAPSHOT.jar
COPY ${JAR_FILE} financy.jar
ENTRYPOINT ["java","-jar","/financy.jar"]
