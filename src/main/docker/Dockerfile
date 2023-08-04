FROM openjdk:8-jdk-alpine
MAINTAINER marcos.rod.ban
#ADD bootstrap.yml /conf/bootstrap.yml
#ADD application.yml /conf/application.yml
ADD eureka-0.0.1-SNAPSHOT.jar eurekaserver.jar
ENTRYPOINT ["java","-jar","/eurekaserver.jar","--spring.config.location=file:/conf/application.yml","--spring.cloud.bootstrap.location=file:/conf/bootstrap.yml"]
