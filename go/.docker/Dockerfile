
FROM golang:alpine as builder

WORKDIR $GOPATH/src/

COPY ./src .

# CGO has to be disabled for alpine
RUN CGO_ENABLED=0 go build -ldflags="-s -w" -o /go/app

FROM scratch

COPY --from=builder /go/app /go/app

EXPOSE 8000

CMD ["/go/app"]