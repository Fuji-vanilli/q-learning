FROM openjdk:17-oracle

VOLUME /temp
COPY target/*.jar config-server.jar

ENTRYPOINT ["java", "-jar", "config-server.jar"]