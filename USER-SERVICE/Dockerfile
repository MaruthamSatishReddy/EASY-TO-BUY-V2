FROM openjdk:17-jdk
WORKDIR /app
COPY . /target/*.jar /app.jar
EXPOSE 9099
CMD ["java", "-jar", "app.jar"]