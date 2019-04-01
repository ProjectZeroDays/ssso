## ss with simple obfs Dockerfile

deploy a ss with simple obfs included

## usage
```bash
docker run -d -e PASSWORD=<YOUR PASSWORD> -p <YOUR EXPOSE PORT>:8388 -p <YOUR EXPOSE UDP PORT>:8388/udp dawncold/ssso:latest
```

e.g.
```bash
docker run -d -e PASSWORD=ssso -p 10086:8388 -p 10086:8388/udp dawncold/ssso:latest
```


## Links

[https://hub.docker.com/r/dawncold/ssso](https://hub.docker.com/r/dawncold/ssso)

[https://github.com/shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)

[https://github.com/shadowsocks/simple-obfs](https://github.com/shadowsocks/simple-obfs)