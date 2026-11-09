FROM golang:1.16
WORKDIR /myapp
EXPOSE 8080
COPY . .
RUN go build .
CMD ["./server"]
