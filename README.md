# Workerman

## How to use?

```
//Server
docker run -it -p 8282:8282 -v /tmp/workerman:/var/www  --name workerman-app io84/workerman:latest sh

//Client
telnet 127.0.0.1 8282
```
