FROM openjdk:17
WORKDIR /app
COPY ./target/MicroserviceItem-1.0.0.jar item.jar
EXPOSE 8080
ENTRYPOINT [ "java","-jar","item.jar" ]