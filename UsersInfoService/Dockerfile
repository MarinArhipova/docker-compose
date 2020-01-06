FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/users-info-service-0.1.jar
ADD ${JAR_FILE} users-info-service-0.1.jar
CMD ["java", "-jar", "/users-info-service-0.1.jar"]