FROM golang:1.26rc3-alpine
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
