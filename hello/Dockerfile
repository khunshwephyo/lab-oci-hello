# does not work yet.
#FROM oraclelinux:7-slim
#MAINTAINER Khun Shwe Phyo <khunshwephyo@gmail.com>
#RUN yum -y install java-1.8.0-openjdk-devel
#COPY build/libs/hello-*-all.jar hello.jar
#EXPOSE 80
#CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-XX:+IdleTuningGcOnIdle", "-Xtune:virtualized", "-jar", "hello.jar"]

FROM jeanblanchard/java:8
COPY build/libs/hello-*-all.jar hello.jar
CMD java -jar hello.jar
EXPOSE 80