---
published: true
title: Linux工具箱
layout: page
order: 1
---

## 网络

* 修改很多linux的tcp参数，抗丢包，提高带宽利用率
  
```
sysctl net.ipv4.tcp_congestion_control
sudo modprobe tcp_bbr
sudo sysctl -w net.core.default_qdisc=fq
sudo sysctl -w net.ipv4.tcp_congestion_control=bbr
```
