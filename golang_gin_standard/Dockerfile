FROM golang:1.24.1
WORKDIR /app
ADD service/ /app
RUN go get . && go build -o app
EXPOSE 1300

ENTRYPOINT ["/app/app"]
