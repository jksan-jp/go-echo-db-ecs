FROM golang:1.21-alpine3.18 AS go
WORKDIR /app
ADD go.mod go.sum main.go ./
RUN go mod download
RUN go build -o main /app/main.go
CMD /app/main
