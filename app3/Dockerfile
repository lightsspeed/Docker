FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y tree curl

RUN curl -fsSL https://get.docker.com -o get-docker.sh && \
    sh get-docker.sh

RUN rm get-docker.sh

VOLUME /var/run/docker.sock

CMD ["bash"]
