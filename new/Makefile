build:
	env GOARCH=arm64 GOOS=linux go build -tags lambda.norpc -ldflags="-s -w" -o bin/bootstrap hello/main.go
	cd ./bin; zip hello.zip bootstrap
deploy:
	AWS_PROFILE=mine sls deploy --verbose