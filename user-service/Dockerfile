FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app/user-service
COPY target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar app.jar"]