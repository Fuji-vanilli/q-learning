FROM openjdk:17-oracle

VOLUME /tmp
COPY target/*.jar discovery-server.jar

ENTRYPOINT ["java", "-jar", "discovery-server.jar"]