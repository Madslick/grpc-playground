FROM golang:1.17-bullseye

RUN apt-get update

RUN apt-get install vim -y

WORKDIR /go/src/github.com/Madslick/grpc-playground/

COPY . .

CMD [ "/bin/bash" ]