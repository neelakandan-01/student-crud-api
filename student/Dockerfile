# Use OpenJDK base image for Java 17
FROM openjdk:17-jdk-slim

# Set working directory in container
WORKDIR /app

# Copy your Spring Boot jar into the container
COPY target/student-crud-api.jar student-crud-api.jar

# Expose the port on which your app will run (default for Spring Boot is 8080)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "student-crud-api.jar"]