FROM golang:1.25rc1-alpine
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
