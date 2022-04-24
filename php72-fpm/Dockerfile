FROM ghcr.io/aurimasvilys/nfq-docker-images/php72-cli:latest

EXPOSE 9000
CMD exec /entrypoint.sh

ADD build /build
RUN bash /build/setup_docker.sh && rm -Rf /build

