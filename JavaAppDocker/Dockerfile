# Use an official OpenJDK 21 runtime as a parent image
FROM openjdk:21-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/JavaAppDocker-1.0-SNAPSHOT.jar /app/app.jar

# Run the Java application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]