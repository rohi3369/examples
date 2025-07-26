FROM golang:1.25rc2
WORKDIR /app
ADD . /app
RUN go build -o app

ENTRYPOINT ["/app/app"]
