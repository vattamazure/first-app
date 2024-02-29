FROM eclipse-temurin:17

RUN mkdir /opt/app

#COPY  ["C:\\Users\\Prasad\\Downloads\\hello-world\\demo\\target\\demo-0.0.1-SNAPSHOT.jar", "/opt/app/"]

COPY /target/demo-0.0.1-SNAPSHOT.jar /opt/app

#COPY ["C:\\Users\\Prasad\\Downloads\\hello-world\\demo\\target\\demo-0.0.1-SNAPSHOT.jar", "/opt/app"]

CMD ["java", "-jar", "/opt/app/demo-0.0.1-SNAPSHOT.jar"]