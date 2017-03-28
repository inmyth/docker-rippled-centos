# docker-rippled-centos

This Rippled is using port 5006. 
Base is Centos.

To build
```
docker build -t rippled-centos . 
```

To run in background
```
docker run -d -p <port>:5006 -t rippled-centos
```

To run in interactive mode
```
docker run -i -p <port>:5006 -t rippled-centos
```



