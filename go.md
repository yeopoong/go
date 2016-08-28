Go
===

개발환경
-------

### Format

```
$ cd /dev/go/src/github.com/yeopoong/go/hanoi
$ gofmt -w hanoi.go 
$ goimports -w hanoi.go 
```

### Run 

```
$ go run hanoi.go
```

### Install 

```
$ cd /dev/go/src
$ go install github.com/yeopoong/go/hanoi 
$ hanoi
```

개발환경
-------

### GOPATH 설정

```
export GOROOT=$HOME/go 
```

Tip: 설치 경로가 /usr/local/go 또는 C:\Go 라면 GOROOT를 설정할 필요가 없다

### GOPATH 설정

```
export GOPATH=$HOME/go/work 
```