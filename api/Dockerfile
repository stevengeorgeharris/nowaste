From golang:latest

ADD . /go/src/github.com/stevengeorgeharris/nowaste/api

# Get any project dependencies here

RUN go get github.com/gorilla/mux

# Install binary then set as entry point

RUN go install github.com/stevengeorgeharris/nowaste/api

ENTRYPOINT /go/bin/api

EXPOSE 3000

