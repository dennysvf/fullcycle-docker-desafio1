  
FROM golang:1.16 as builder

WORKDIR /go/src/app

COPY . .

RUN CGO_ENABLED=0 go build -o /app main.go

FROM scratch as final

COPY --from=builder /app /app

CMD ["/app"]