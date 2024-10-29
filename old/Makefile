build:
	env GOOS=linux go build -ldflags="-s -w" -o bin/hello hello/main.go
	cd bin; zip hello.zip hello
deploy:
	AWS_PROFILE=mine sls deploy --verbose