FROM golang:1.21-alpine3.18 AS go
WORKDIR /app
COPY go.mod go.sum main.go ./
RUN go mod download \
&& go build -o main /app/main.go
CMD ["/app/main"]
