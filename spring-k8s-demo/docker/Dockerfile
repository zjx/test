FROM adoptopenjdk/openjdk11:jre-11.0.6_10

ADD ./target/demo-0.0.1-SNAPSHOT.jar /opt

WORKDIR /opt

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "demo-0.0.1-SNAPSHOT.jar"]

