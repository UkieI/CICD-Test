# Chỉ định image base
FROM openjdk:17.0.1-jdk-slim

# Sao chép file JAR từ thư mục target vào container với tên là app.jar
COPY target/server_student*.jar app.jar

# Mở cổng 8080 cho container
EXPOSE 8080

# Chạy ứng dụng Spring Boot
ENTRYPOINT ["java", "-jar", "app.jar"]