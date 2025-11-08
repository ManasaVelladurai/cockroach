FROM golang:1.25.4
WORKDIR /build
COPY . .
RUN ["/build/build.sh"]
ENTRYPOINT ["/build/entrypoint.sh"]
