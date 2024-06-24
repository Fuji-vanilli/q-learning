FROM openjdk:17-oracle

VOLUME /tmp
COPY /target/*.jar category-service.jar

ENTRYPOINT ["java", "-jar", "category-service.jar"]