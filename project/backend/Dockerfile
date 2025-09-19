# Use Java 17
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy built jar
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Run Spring Boot
ENTRYPOINT ["java","-jar","/app/app.jar"]

