For beginners, if there any build issue with golang can use following command to execute the code correctly:
$ export GO111MODULE=auto
$ go build
$ go run main.go

If you can not connect the localhost:8080 and shows bind issue then you may follow below steps to connect with the localhost server:
$ lsof -i :8080
$ kill -9 pid
