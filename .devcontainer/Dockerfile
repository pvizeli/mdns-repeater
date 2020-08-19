# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.134.0/containers/cpp/.devcontainer/base.Dockerfile
ARG VARIANT="buster"
FROM mcr.microsoft.com/vscode/devcontainers/cpp:0-${VARIANT}

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
     && apt-get -y install --no-install-recommends \
        clang-format
