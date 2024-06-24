FROM openjdk:17-oracle

VOLUME /tmp
COPY /target/*.jar gateway-service.jar

ENTRYPOINT ["java", "-j", "gateway-service.jar"]