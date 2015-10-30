FROM java:8-jdk

ADD . /app

WORKDIR /app

RUN ./gradlew clean build

EXPOSE 8080

ENTRYPOINT ["java -jar build/libs/spring-boot-web-application.jar"]
