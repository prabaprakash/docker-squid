# forked from sameersbn/squid:3.3.8-23
# Configured squid for Forward Proxy 
# Working Forward Proxy

Steps
```
docker build . --tag squidForwardProxy

docker run -it -p 3200:3200 squidForwardProxy
```
