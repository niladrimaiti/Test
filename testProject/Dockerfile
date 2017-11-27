FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/testProject-0.1.0.jar app1.jar
EXPOSE 8070
ENTRYPOINT  ["java","-jar", "app1.jar"]
