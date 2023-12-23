# Use an official OpenJDK runtime as a base image
FROM openjdk:17-jdk-alpine

# Set the working directory to /app
WORKDIR /app

# Copy the packaged JAR file into the container at /app
COPY ${WORKSPACE}/ecom-backend/target/ecommerce-0.0.1-SNAPSHOT.jar /app/ecommerce.jar

# Specify the default command to run your application
CMD ["java", "-jar", "ecommerce.jar"]