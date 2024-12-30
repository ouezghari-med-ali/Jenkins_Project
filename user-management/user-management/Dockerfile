# Use a base image
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app

# Copy project files
COPY . /app

# Expose the application port
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "user-management-0.0.1-SNAPSHOT.jar"]
