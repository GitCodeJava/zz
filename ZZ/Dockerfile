FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar zzapp.jar
ENTRYPOINT ["java","-jar","/zzapp.jar"]