Possibly go build cause some issue, in this case use:
$ export GO111MODULE=auto
$ go build
$ go run main.go 

Then check localhost server:
localhost:8080

If process is running it may give bind issue and thus not able to connect 
the localhost then use the following command:
$ lsof -i :8080
$ kill -9 pid