# code-server-gocv
**Compiled gocv based on the linuxserver/code-server.**  
Default SUDO_PASSWORD=1q2w3e4r!  

**[Docker Hub](https://hub.docker.com/repository/docker/gron1gh1/code-server-gocv/general)**

## Run
```sh
> sudo docker run -itd \
-p 80:8443 \
-v $PWD/data/code-server/config:/config \
--restart unless-stopped \
gron1gh1/code-server-gocv
```

## Input code-server Terminal
```sh
> go get -u -d gocv.io/x/gocv
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
