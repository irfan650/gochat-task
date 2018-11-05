# gochat-task
 
 A client server chat based on TCP
 
# Prerequsit
- install go language https://golang.org/doc/install
- set the path as $GOPATH=go-work-space

# Usage

Open command promt and run


  $ go get github.com/irfan650/gochat-task/...
  
  
It will get the code install it into go work space 

# To start server 

 $GOPATH/bin/gochat

# To start client

$GOPATH/bin/gochat 127.0.0.1 3200

#### In case of issues running from bin

Run with go run command 

go run /src/github.com/irfan650/gochat-task/gochat/gochat.go
