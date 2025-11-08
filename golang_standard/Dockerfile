FROM golang:1.25.4
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
