FROM frolvlad/alpine-oraclejdk8:slim
MAINTAINER hrjin <hyunlee@bluedigm.com>

VOLUME /tmp
ARG JAR_FILE
ADD spring-music.jar spring-music.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-music.jar"