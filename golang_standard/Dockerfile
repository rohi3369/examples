FROM golang:1.24.2
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
