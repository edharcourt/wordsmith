FROM golang

WORKDIR /web

COPY dispatcher.go .

COPY static .

RUN go build dispatcher.go

CMD ["./dispatcher"]