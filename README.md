# Squid Forward Proxy
Configured Squid for Forward Proxy 

Steps
```
docker build . --tag squidForwardProxy

docker run -it -p 3200:3200 squidForwardProxy
```
```
Note:
forked from sameersbn/squid:3.3.8-23
```
