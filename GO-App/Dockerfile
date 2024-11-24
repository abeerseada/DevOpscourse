FROM golang:1.20-alpine AS builder

WORKDIR /data

RUN go mod init goapp 

COPY main.go .

RUN go mod download 

RUN go build -o main .

FROM alpine:latest

RUN apk add --no-cache ca-certificates

WORKDIR /root 

COPY --from=builder /data/main .

EXPOSE 8080 

CMD ["./main"]
