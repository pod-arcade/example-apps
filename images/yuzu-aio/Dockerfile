FROM ghcr.io/pod-arcade/desktop:main

# Install all necessary packages
RUN apt-get update && \
    apt-get install -y \
    mesa-utils-extra \
    yuzu \
    pulseaudio \
    wget && \
    rm -rf /var/lib/apt/lists/*

ENV EXTRA_SWAY_COMMANDS "/usr/games/yuzu"