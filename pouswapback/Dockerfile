FROM golang:1.21.1

WORKDIR /go/src/app

COPY . .

RUN go build -o app

CMD ["./app"]
