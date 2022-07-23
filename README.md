# vagrant-docker-provider

tweak of https://github.com/mcwarman/vagrant-docker-provider

## List

|         OS         |                         image                        |
|:------------------:|:----------------------------------------------------:|
| CentOS 7           | `seonghyeon/vagrant-docker-provider:centos7`         |
| CentOS 7 (systemd) | `seonghyeon/vagrant-docker-provider:centos7-systemd` |

## build

(TBD: do this with makefile)

```sh
cd centos7
docker buildx build --platform=linux/amd64,linux/arm64 -t seonghyeon/vagrant-docker-provider:centos7 . --push
```

```sh
cd centos7-systemd
docker buildx build --platform=linux/amd64,linux/arm64 -t seonghyeon/vagrant-docker-provider:centos7-systemd . --push
```
