FROM openjdk:17-oracle

VOLUME /tmp
COPY target/*.jar quiz-service.jar

ENTRYPOINT ["java", "-jar", "quiz-service.jar"]