FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/sissi_velas-0.0.1.jar
COPY ${JAR_FILE} app_sissivelas.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_sissivelas.jar"]