FROM ubuntu:latest

# Install necessary utilities
RUN apt-get update && \
    apt-get install -y tree curl

# Install Docker client
RUN curl -fsSL https://get.docker.com -o get-docker.sh && \
    sh get-docker.sh

# Cleanup
RUN rm get-docker.sh

# Expose Docker socket to the container
VOLUME /var/run/docker.sock

CMD ["bash"]
#