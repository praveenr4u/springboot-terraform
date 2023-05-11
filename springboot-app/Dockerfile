FROM openjdk:8
EXPOSE 8080
#ADD target/springboot-app.jar springboot-app.jar
COPY target/springboot-app.jar springboot-app.jar
ENTRYPOINT ["java","-jar","/springboot-app.jar"]