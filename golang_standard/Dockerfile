FROM golang:1.26.0
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
