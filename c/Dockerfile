FROM stardustdl/dev-containers:mirror-bionic

RUN apt-get update && \
    apt-get install -y \
        build-essential \
        libelf-dev \
        vim \
        git \
        python3 \
        python3-pip \
        tmux \
        jq \
        man \
        iproute2 iproute2-doc \
        && \
    python3 -m pip install --upgrade pip --no-cache-dir pip -U && \
    python3 -m pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple && \
    rm -rf /var/lib/apt/lists/*

