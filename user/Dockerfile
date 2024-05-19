FROM golang:1.18-alpine

RUN mkdir /app

RUN addgroup -S developer
RUN adduser -S -D -h /app raka developer
RUN chown -R raka:developer /app
USER raka

COPY main.go /app

EXPOSE 8080
CMD go run /app/main.go