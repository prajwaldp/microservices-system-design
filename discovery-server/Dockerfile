FROM adoptopenjdk/openjdk11:jdk-11.0.8_10-alpine
ADD target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /app.jar" ]
