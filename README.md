# hello-world
### First Google GO program.

In the trusty shell of your choice

```
cd $SOURCE_LOCATION
wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
cd $INSTALL_LOCATION && tar -xzf ${SOURCE_LOCATION}/go1.7.3.linux-amd64.tar.gz
export GOROOT=$INSTALL_LOCATION/go
export GOBIN=$MY_PROGS/bin
export PATH=$GOROOT/bin:$GOBIN:$PATH
```

