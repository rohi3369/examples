FROM golang:1.26rc2
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
