FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/testProject-0.1.0.jar app.jar
EXPOSE 8090
ENTRYPOINT  ["java","-jar", "app.jar"]