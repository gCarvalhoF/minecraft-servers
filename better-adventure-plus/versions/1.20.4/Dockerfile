FROM eclipse-temurin:21-jre

EXPOSE 3000

WORKDIR /server

RUN apt-get update && apt-get install curl

COPY . /server

ENTRYPOINT [ "sh", "./start.sh" ]