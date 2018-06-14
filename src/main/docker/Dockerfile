FROM openjdk:8-jdk-alpine
MAINTAINER hrjin <hyunlee@bluedigm.com>

VOLUME /tmp
ADD spring-music.jar spring-music.jar
EXPOSE 7878
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-music.jar"]