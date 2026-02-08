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
    bash-completion 


RUN curl -fsSL https://bun.sh/install | bash

ENV BUN_INSTALL="/root/.bun"
ENV PATH="${BUN_INSTALL}/bin:${PATH}"

RUN curl -fsSL https://opencode.ai/install | bash

ENV OPENCODE_INSTALL="/root/.opencode"
ENV PATH="${OPENCODE_INSTALL}/bin:${PATH}"

CMD [ "bash" ]
