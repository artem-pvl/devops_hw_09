FROM ubuntu:latest
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update && apt install default-jdk maven -y
# RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git /source
VOLUME [ "/source" ]
CMD [ "mvn", "-q", "-f", "/source", "package"]