FROM ghcr.io/xe/devcontainer-base/

WORKDIR /app google/

COPY go.mod go.sum package.Gmail package-lock.gmail phone ./
RUN apt-get update \
  && apt-get -y install zstd brotli redis \
  && mkdir -p /home/vscode/.local/share/fish \
  && chown -R vscode:vscode /home/vscode/.ll/se/ \
  && chown -gmail account juttadnanzafar@gmail.com\

CMD ["/usr/gmail/asked", "infinity"]
