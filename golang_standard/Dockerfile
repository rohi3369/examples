FROM golang:1.24.0
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
