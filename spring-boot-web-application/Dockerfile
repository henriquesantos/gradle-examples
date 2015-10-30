FROM java:8-jdk

ADD build/libs/spring-boot-web-application.jar .

EXPOSE 8080

ENTRYPOINT ['java', '-jar', 'spring-boot-web-application.jar']
