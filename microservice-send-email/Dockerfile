FROM eclipse-temurin:8-jre-alpine
VOLUME /tmp
COPY target/microservicecicd-send-email.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
