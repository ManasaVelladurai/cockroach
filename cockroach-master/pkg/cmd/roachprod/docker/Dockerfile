FROM golang:1.22.9
WORKDIR /build
COPY . .
RUN ["/build/build.sh"]
ENTRYPOINT ["/build/entrypoint.sh"]
