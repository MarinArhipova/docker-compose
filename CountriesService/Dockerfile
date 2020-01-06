FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/countries-service-0.1.jar
ADD ${JAR_FILE} countries-service-0.1.jar
CMD ["java", "-jar", "/countries-service-0.1.jar"]