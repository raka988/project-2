FROM golang:1.18-alpine

RUN mkdir /app
copy main.go /app

EXPOSE 8080
ENTRYPOINT ["go", "run"]
CMD ["/app/main.go"]