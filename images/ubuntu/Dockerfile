FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y \
        bash \
        curl \
        ca-certificates \
        tzdata \
    && apt-get clean && \
    rm -rf /var/lib/apt/lists/*

CMD ["bash"]
