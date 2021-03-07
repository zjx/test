mvn clean package
D:\D\d\JDK\jdk1.8.0_231\bin\java -jar .\target\demo-0.0.1-SNAPSHOT.jar


java -Dspring.profiles.active=test -jar ./target/demo-0.0.1-SNAPSHOT.jar
java -jar ./target/demo-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod

http://127.0.0.1:8080/demo

http://127.0.0.1:8080/swagger-ui.html

http://127.0.0.1:8080/v2/api-docs