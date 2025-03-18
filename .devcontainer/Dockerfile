FROM ubuntu:20.04
RUN apt-get update && apt-get install -y \
    git \
    build-essential \
    cmake \
    g++ \
    libpq-dev \
    libssl-dev \
&& rm -rf /var/lib/apt/lists/*
WORKDIR /workspaces/stellar-core
CMD ["bash"]
