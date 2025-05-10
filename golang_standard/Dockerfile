FROM golang:1.24.3
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
