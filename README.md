# code-server-gocv
**Compiled gocv based on the linuxserver/code-server.**  
Default SUDO_PASSWORD=1q2w3e4r!  

**[Docker Hub](https://hub.docker.com/repository/docker/gron1gh1/code-server-gocv/general)**

## Run
```sh
> git clone --recurse-submodules https://github.com/gron1gh1/code-server-gocv.git
> docker-compose up -d
```

## Input code-server Terminal
```sh
> cd $GOPATH/src/gocv.io/x/gocv
> go run ./cmd/version/main.go
```
**Result**
```
gocv version: 0.24.0
opencv lib version: 4.4.0
```

## Screenshot
![screenshot](https://i.imgur.com/kAByquL.png)
