FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/sale-service-0.0.1.jar
COPY ${JAR_FILE} app_sale_service.jar
ENTRYPOINT ["java", "-jar", "app_sale_service.jar"]