FROM mcr.microsoft.com/devcontainers/base:ubuntu

# install dependencies
RUN apt-get update && \
    apt-get install -y git curl && \
    apt-get install -y make cmake gfortran libcoarrays-dev libopenmpi-dev libcoarrays-openmpi-dev libcaf-openmpi-3 && \
    apt-get clean
