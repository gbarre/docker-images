FROM ubuntu:18.04

RUN apt-get update; \
    DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
      curl \
      telnet \
      iputils-ping \
      dnsutils \
      tcpdump \
      vim \
      bash-completion \
      less \
      tree \
      screen; \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
