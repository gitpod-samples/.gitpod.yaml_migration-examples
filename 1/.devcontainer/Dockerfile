FROM mcr.microsoft.com/devcontainers/base:latest

USER vscode

RUN git config --global pull.rebase false \
    && git config --global fetch.prune true \
    && git config --global diff.colorMoved zebra