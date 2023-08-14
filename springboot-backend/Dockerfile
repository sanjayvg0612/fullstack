FROM maven:3.8-openjdk-17
WORKDIR /springboot-backend/
COPY target/springboot-backend-0.0.1-SNAPSHOT.jar springboot-backend.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","springboot-backend.jar"]
