# Go

Compiled, high-level, statically typed, memory safe programming language. 


## Install compiler

```bash
curl "https://dl.google.com/go/$(curl https://golang.org/VERSION?m=text).linux-amd64.tar.gz" -f | sudo tar -C /usr/local -xz
echo 'export PATH=$PATH:/usr/local/go/bin' >> $HOME/.profile
echo 'export GOPATH=$HOME/.go' >> $HOME/.profile

```

## Run script

```bash
go run file.go
```