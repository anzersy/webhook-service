webhook-service
========

A microservice that does micro things.

## Building

`mkdir -p $GOPATH/src/github.com/rancher && cd $GOPATH/src/github.com/rancher && git clone https://github.com/anzersy/webhook-service.git`
`cd $GOPATH/src/github.com/rancher/webhook-service && mv main.go webhook-service.go`
`go install $GOPATH/src/github.com/rancher/webhook-service/webhook-service.go`
`cp $GOPATH/bin/webhook-service $GOPATH/src/github.com/rancher/webhook-service/`

## Running

`./webhook-service`

