FROM openjdk:8-jdk-alpine

RUN apk update

WORKDIR /work/

COPY target/ocexpertcamp-thorntail.jar /work/ocexpertcamp-thorntail.jar
COPY target/ocexpertcamp.war /work/ocexpertcamp.war
RUN chmod 775 /work
EXPOSE 8080

ENTRYPOINT ["java",  "-jar", "/work/ocexpertcamp-thorntail.jar" ,"-Djava.net.preferIPv4Stack=true"]