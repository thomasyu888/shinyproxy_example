FROM openjdk:8-jre

WORKDIR /opt/shinyproxy

RUN wget https://www.shinyproxy.io/downloads/shinyproxy-3.0.1.jar

COPY application.yml application.yml

CMD ["java", "-jar", "shinyproxy-3.0.1.jar"]