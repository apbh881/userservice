FROM java:8-jdk
RUN mkdir /app
WORKDIR /app
COPY target/user_service-0.0.1-SNAPSHOT.jar /app
EXPOSE 9001

ENTRYPOINT ["java", "-jar", "user_service-0.0.1-SNAPSHOT.jar"]