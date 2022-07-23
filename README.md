# vagrant-docker-provider

## List

| OS                 | image                                                | size                                                                                                              |
|--------------------|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| RockyLinux 8       | `seonghyeon/vagrant-docker-provider:rockylinux8`     | ![Docker Image Size](https://img.shields.io/docker/image-size/seonghyeon/vagrant-docker-provider/rockylinux8)     |
| RockyLinux 9       | `seonghyeon/vagrant-docker-provider:rockylinux9`     | ![Docker Image Size](https://img.shields.io/docker/image-size/seonghyeon/vagrant-docker-provider/rockylinux9)     |
| CentOS 7           | `seonghyeon/vagrant-docker-provider:centos7`         | ![Docker Image Size](https://img.shields.io/docker/image-size/seonghyeon/vagrant-docker-provider/centos7)         |
| CentOS 7 (systemd) | `seonghyeon/vagrant-docker-provider:centos7-systemd` | ![Docker Image Size](https://img.shields.io/docker/image-size/seonghyeon/vagrant-docker-provider/centos7-systemd) |

## usage

```sh
make build IMAGE_TAG=rockylinux8
make build IMAGE_TAG=rockylinux9
make build IMAGE_TAG=centos7
make build IMAGE_TAG=centos7-systemd
```

## credits
- https://github.com/mcwarman/vagrant-docker-provider
- https://github.com/rofrano/vagrant-docker-provider

