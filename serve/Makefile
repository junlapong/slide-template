SHELL:=/bin/bash

all: macos win64

install:
	go install

macos:
	GOOS=darwin GOARCH=amd64 go build -o serve

win64:
	GOOS=windows GOARCH=amd64 go build -o serve.exe

clean:
	rm serve
	rm serve.exe
