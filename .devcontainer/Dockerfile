ARG VARIANT=focal
FROM mcr.microsoft.com/vscode/devcontainers/cpp:${VARIANT}
# COPY library-scripts/github-debian.sh /tmp/library-scripts/
RUN apt update -y
RUN apt install python3 clangd -y
RUN python3 -m pip install --upgrade pip setuptools
RUN python3 -m pip install norminette
# RUN bash /tmp/library-scripts/github-debian.sh
