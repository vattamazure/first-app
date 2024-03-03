 FROM ubuntu
# RUN sudo root
 RUN apt-get update
 RUN apt install -y default-jdk
 RUN apt install default-jre
 RUN mkdir /opt/app
 COPY /target/demo-0.0.1-SNAPSHOT.jar /opt/app
 CMD java -jar /opt/app/demo-0.0.1-SNAPSHOT.jar
