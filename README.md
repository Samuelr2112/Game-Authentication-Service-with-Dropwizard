# Authentication Service for Gaming Platform
# Project Overview
The GameAuth project is a Java-based application developed to manage user authentication for a gaming platform. The service provides secure login and user verification features, ensuring that sensitive user data is handled with care. Built using the Maven framework, the project allows for efficient dependency management and straightforward project builds, making it easy to maintain and deploy.

# Features
The primary function of the GameAuth project is to manage secure user authentication. The service also includes a health check feature, which provides an endpoint to monitor the application’s operational status and ensure that everything is functioning as expected. The project is configured using a config.yml file and can be run as a standalone application through a Java .jar file.

# How to Run
To run the project, first build the application by executing mvn clean install in your terminal. Once the build is complete, start the application by running java -jar target/GameAuth-0.0.1-SNAPSHOT.jar server config.yml. You can verify that the application is running by visiting http://localhost:8080. To check the health of the application, visit http://localhost:8081/healthcheck for real-time status updates.
