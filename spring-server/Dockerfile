FROM openjdk:11
COPY /var/lib/jenkins/workspace/test-build/spring-server/target/swagger-spring-1.0.0.jar app.jar
ENTRYPOINT [ "java" , "-jar" , "app.jar"]
