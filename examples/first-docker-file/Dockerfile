FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the jar file from Maven build
COPY target/my-multi-step-app-1.0.0.jar app.jar

# Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]
