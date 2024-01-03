FROM mcr.microsoft.com/vscode/devcontainers/cpp
# COPY library-scripts/github-debian.sh /tmp/library-scripts/
RUN apt-get update
RUN apt install python3 clangd-12
RUN python3 -m pip install --upgrade pip setuptools
RUN python3 -m pip install norminette
# RUN bash /tmp/library-scripts/github-debian.sh
