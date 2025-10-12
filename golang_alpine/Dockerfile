FROM golang:1.25.2-alpine
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
