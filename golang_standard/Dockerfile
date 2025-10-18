FROM golang:1.25.3
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
