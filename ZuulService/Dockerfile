FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/zuul-service-0.1.jar
ADD ${JAR_FILE} zuul-service-0.1.jar
CMD ["java", "-jar", "/zuul-service-0.1.jar"]