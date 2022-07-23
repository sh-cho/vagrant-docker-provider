# vagrant-docker-provider

tweak of https://github.com/mcwarman/vagrant-docker-provider

## List

|    OS    |                     image                    |
|:--------:|:--------------------------------------------:|
| CentOS 7 | `seonghyeon/vagrant-docker-provider:centos7` |

## build

```sh
cd centos7
docker buildx build -t seonghyeon/vagrant-docker-provider:centos7 . --push
```

