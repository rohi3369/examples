FROM golang:1.25.1
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
