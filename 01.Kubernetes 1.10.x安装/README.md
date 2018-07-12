# 部署说明

## 部署环境

虚拟机配置：4台虚拟机，每台8vCPU、16G内存、3个20G虚拟硬盘，1个用于安装系统，另外两个20G虚拟硬盘用于glusterfs。
操作系统：CentOS 7.5，64bit，minimal安装；

## 相关镜像下载

由于gcr.io无法国内访问，本文档需要的docker镜像可以从我的网盘上下载到，通过`docker load -i xxx.tar`导入即可，
[镜像下载地址](https://pan.baidu.com/s/1VMM2aUZuCac4OR0kXkwDXw)

## 部署步骤

1. [01.系统准备.md](01.系统准备.md)
1. [02.CA和证书创建.md](02.CA和证书创建.md)
1. [03.部署etcd.md](03.部署etcd.md)
1. [04.部署kubectl.md](04.部署kubectl.md)
1. [05.部署flannel.md](05.部署flannel.md)
1. [06.部署kube-apiserver.md](06.部署kube-apiserver.md)
1. [07.部署kube-controller-manager.md](07.部署kube-controller-manager.md)
1. [08.部署kube-scheduler.md](08.部署kube-scheduler.md)
1. [09.部署kubelet.md](09.部署kubelet.md)
1. [10.部署kube-proxy.md](10.部署kube-proxy.md)
1. [11.部署CoreDNS.md](11.部署CoreDNS.md)
1. [12.部署Dashboard.md](12.部署Dashboard.md)
1. [13.部署Heaspter.md](13.部署Heaspter.md)
1. [14.部署Metrics Server.md](14.部署Metrics Server.md)
1. [15.部署Traefik ingress.md](15.部署Traefik ingress.md)
1. [16.部署Glusterfs.md](16.部署Glusterfs.md)
1. [17.部署EFK.md](17.部署EFK.md)
1. [18.部署Prometheus.md](18.部署Prometheus.md)