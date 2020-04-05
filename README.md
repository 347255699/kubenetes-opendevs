# kubenetes-opendevs

如何使用 k8s 集群改造现有的糟糕的开发测试集成环境 ？

## 项目启动环境准备

1. 两台 linux x86_64 机器
2. 配置穿透，提供登录账户

准备机器

* ubuntu18 2core 2G
* ubuntu18 2core 4G

## java 应用容器化

1. 容器化 api, service, mysql
2. 容器化 ngnix，注意将配置和html路径通过 sidecar 容器共享 volumn

