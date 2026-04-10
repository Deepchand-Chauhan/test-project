FROM bellsoft/liberica-openjdk-alpine
EXPOSE 8080
ADD target/test-project-0.0.1-SNAPSHOT.jar test-project-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar","/test-project-0.0.1-SNAPSHOT.jar"]