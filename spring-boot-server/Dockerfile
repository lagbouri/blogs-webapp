FROM adoptopenjdk/openjdk11:latest
WORKDIR /app
COPY . .
RUN ./mvnw package
CMD ["java", "-jar", "target/your-spring-boot-app.jar"]
