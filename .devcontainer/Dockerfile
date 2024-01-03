ARG VARIANT=buster
FROM mcr.microsoft.com/vscode/devcontainers/cpp:0-${VARIANT}
# COPY library-scripts/github-debian.sh /tmp/library-scripts/
RUN apt-get update
RUN apt-get install python3 clangd-17 -y
RUN python3 -m pip install --upgrade pip setuptools
RUN python3 -m pip install norminette
# RUN bash /tmp/library-scripts/github-debian.sh
