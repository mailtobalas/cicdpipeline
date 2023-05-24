FROM openjdk:8u342-slim-buster
EXPOSE 8080
ADD  target/Cicd-integration.jar Cicd-integration.jar

ENTRYPOINT ["java","-jar","Cicd-integration.jar"]