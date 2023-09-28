# ステージ1
FROM golang:1.21-alpine3.18 AS go
WORKDIR /app
COPY go.mod go.sum main.go ./
RUN go mod download \
&& go build -o main /app/main.go

# ステージ2
FROM alpine:3.18
WORKDIR /app
COPY --from=go /app/main .
CMD ["/app/main"]
