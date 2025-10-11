FROM golang:1.25.2
WORKDIR /app
ADD service/ /app
RUN go get . && go build -o app
EXPOSE 1300

ENTRYPOINT ["/app/app"]
