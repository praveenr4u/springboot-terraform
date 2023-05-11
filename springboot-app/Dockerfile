FROM openjdk:8
EXPOSE 8080
ADD ./springboot-app/target/springboot-k8s-demo.jar springboot-k8s-demo.jar
ENTRYPOINT ["java","-jar","/springboot-k8s-demo.jar"]