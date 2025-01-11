# Chỉ định image base
FROM openjdk:17.0.1-jdk-slim

# Sao chép file JAR từ thư mục target vào container với tên là app.jar
COPY target/server_student-0.0.1-SNAPSHOT.jar ctdt-api-images.jar

# Mở cổng 8080 cho container
EXPOSE 8080

# Chạy ứng dụng Spring Boot
ENTRYPOINT ["java", "-jar", "/ctdt-api-images.jar"]