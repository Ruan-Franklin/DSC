# FROM openjdk:17-jdk-slim

#COPY grupos-partidas-apis-0.0.1-SNAPSHOT.jar /echo.war

FROM maven:3.8.4-openjdk-17-slim
COPY target/ProjetoMaven-1.0-SNAPSHOT.jar /ProjetoMaven-1.0-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/ProjetoMaven-1.0-SNAPSHOT.jar"]
 