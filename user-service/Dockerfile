FROM openjdk:11
EXPOSE 9002
ADD target/user-service-docker.jar user-service-docker.jar
ENTRYPOINT ["java","-jar","/user-service-docker.jar"]