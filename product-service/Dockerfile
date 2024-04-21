FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/product-service-0.0.1.jar
COPY ${JAR_FILE} app_product_service.jar
ENTRYPOINT ["java", "-jar", "app_product_service.jar"]