FROM ubuntu:23.10

# Install all necessary packages
RUN apt-get update && \
    apt-get install -y \
    mesa-utils-extra \
    yuzu \
    pulseaudio \
    wget && \
    rm -rf /var/lib/apt/lists/*


ENTRYPOINT [ "/usr/games/yuzu" ]

