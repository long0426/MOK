# 使用官方的 JDK 17 映像作為基礎映像
FROM registry.hub.docker.com/library/openjdk:17.0.1-jdk-slim

# 複製 CCA.jar 到容器中的 /app 資料夾
COPY CCA-1.0.0-SNAPSHOT.jar /app/CCA-1.0.0-SNAPSHOT.jar

# 設定工作目錄為 /app
WORKDIR /app

# 執行 Java 程式
CMD ["java", "-jar", "CCA-1.0.0-SNAPSHOT.jar"]