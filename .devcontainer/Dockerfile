FROM alpine:latest
RUN apk add --no-cache \
    curl \
    bash \
    git \
    unzip \
    xz \
    sudo \
    tzdata \
    libc6-compat \
    build-base \
    zlib-dev \
    libffi-dev \
    bash-completion \


RUN curl -fsSL https://bun.sh/install | bash
RUN curl -fsSL https://opencode.ai/install | bash

CMD [ "bash" ]
