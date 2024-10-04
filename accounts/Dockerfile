FROM openjdk:21-jdk-slim
MAINTAINER randrindev.com
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} accounts.jar
ENTRYPOINT ["java","-jar","/accounts.jar"]