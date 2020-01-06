FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/service-registry-0.1.jar
ADD ${JAR_FILE} service-registry-0.1.jar
CMD ["java", "-jar", "/service-registry-0.1.jar"]