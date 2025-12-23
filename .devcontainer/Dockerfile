FROM ubuntu:23.10

# install dependencies
RUN apt-get -yq update && \
    apt-get install -yq git curl && \
    apt-get install --no-install-recommends -yq make cmake gfortran libcoarrays-dev libopenmpi-dev libcoarrays-openmpi-dev libcaf-openmpi-3&& \
    apt-get clean -q