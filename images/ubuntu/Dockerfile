FROM ubuntu:22.04

# Disable interactive prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Install basic system utilities
RUN apt-get update && \
    apt-get install -y \
        bash \
        curl \
        ca-certificates \
        tzdata \
    && apt-get clean && \
    rm -rf /var/lib/apt/lists/*

CMD ["bash"]
