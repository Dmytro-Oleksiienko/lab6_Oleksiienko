FROM eclipse-temurin:17-jre-alpine
VOLUME /tmp

COPY complete/target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
