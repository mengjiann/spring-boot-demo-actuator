FROM java:8-jre-alpine
VOLUME /var/www
EXPOSE 8080

COPY ./target/demo-0.0.1-SNAPSHOT.jar  /var/www/

ENTRYPOINT ["java","-jar","/var/www/demo-0.0.1-SNAPSHOT.jar"]
