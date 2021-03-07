FROM huwanyang168/centos7_jdk8:v1.2

MAINTAINER zjx <zjx@github.com>

ADD demo-0.0.1-SNAPSHOT.jar /opt

WORKDIR /opt

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "demo-0.0.1-SNAPSHOT.jar"]

