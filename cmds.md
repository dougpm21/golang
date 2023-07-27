go build
go run
go get
go mod init
go mod tidy

go list -f '{{.Target}}'
Go bin directory

export PATH=$PATH:/go/bin/

go env -w GOBIN=/path/to/your/bin

go get .