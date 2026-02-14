FROM postgres:17.6

USER root

RUN apt-get update && apt-get install -y \
    bsdutils \
    procps \
    iproute2 \
    netcat-openbsd \
    vim \
    less \
    curl \
    bsdmainutils \
    && rm -rf /var/lib/apt/lists/*

USER postgres
