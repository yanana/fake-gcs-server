FROM alpine:3.14.2

RUN apk add --no-cache mailcap
ADD fake-gcs-server /bin/fake-gcs-server
ENTRYPOINT ["/bin/fake-gcs-server", "-data", "/data"]
