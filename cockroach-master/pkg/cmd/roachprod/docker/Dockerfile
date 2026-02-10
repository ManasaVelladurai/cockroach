FROM golang:1.26rc3
WORKDIR /build
COPY . .
RUN ["/build/build.sh"]
ENTRYPOINT ["/build/entrypoint.sh"]
