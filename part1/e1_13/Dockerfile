FROM openjdk

EXPOSE 8080

COPY ./spring-example-project /button-app
WORKDIR /button-app

RUN ./mvnw package
CMD java -jar ./target/docker-example-1.1.3.jar