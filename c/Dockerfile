FROM stardustdl/dev-containers:mirror-bionic

RUN apt-get update && \
    apt-get install -y \
        build-essential \
        libelf-dev \
        vim \
        git \
        python3 \
        tmux \
        jq \
        man \
        iproute2 iproute2-doc \
        && \
    pip3 install --no-cache-dir pip -U && \
    rm -rf /var/lib/apt/lists/*

