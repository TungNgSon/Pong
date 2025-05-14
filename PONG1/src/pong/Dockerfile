# Dùng image chính thức chứa JDK (Java Development Kit)
FROM openjdk:17

# Tạo thư mục làm việc trong container
WORKDIR /app

# Sao chép file Java vào container
COPY Pong.java .

# Compile file Java
RUN javac Pong.java

# Chạy ứng dụng
CMD ["java", "Pong"]

