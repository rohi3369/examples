FROM golang:1.25.0-alpine
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
