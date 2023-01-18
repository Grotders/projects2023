FROM openjdk:17-alpine
WORKDIR /app
ADD /build/libs/kafka-ui-0.0.1.jar spring-kafka-ui.jar
ENTRYPOINT ["java", "-jar", "spring-kafka-ui.jar"]