FROM eclipse-temurin:17-jdk-jammy
EXPOSE 8080
WORKDIR /app
ADD target/test-project-0.0.1-SNAPSHOT.jar test-project-0.0.1.jar
ENTRYPOINT ["java", "-jar","/app/test-project-0.0.1.jar"]