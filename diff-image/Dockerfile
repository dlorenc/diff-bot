FROM ubuntu
RUN apt-get update && apt-get install curl jq -yq
RUN curl -LO https://storage.googleapis.com/container-diff/latest/container-diff-linux-amd64 && chmod +x container-diff-linux-amd64 && mv container-diff-linux-amd64 /usr/local/bin/container-diff
