# docker-frpc
![Docker Automated build](https://img.shields.io/docker/automated/metajs/frpc.svg)
![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/metajs/frpc/latest.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/metajs/frpc.svg)


# usage

- 将frpc.ini 放到/conf下
```
docker run --name=frpc --network=host -v=/conf:/conf -d --restart=always metajs/frpc
```

## other
- [docker-frpc](https://github.com/broven/docker-frpc) 客户端
- [frpc example](https://github.com/fatedier/frp/blob/master/conf/frps_full.ini)
- [centos-boot.sh](https://github.com/broven/centos-boot.sh) 初始化配置一台centos 服务器
