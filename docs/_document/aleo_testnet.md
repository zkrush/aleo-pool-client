# ALEO测试网挖矿教程

## 支持设备

操作系统：Window、Linux

GPU：N卡



## 矿池节点地址

stratum+tcp://aleo.zkrush.com:3030



## 一、添加挖矿账号

1、 参考文档 [添加挖矿账号](/_document/miner_account?id=添加挖矿账号)



## 二、获取挖矿客户端

 1、客户端下载地址: https://github.com/zkrush/aleo-pool-client/releases

> 选择适合您操作系统的版本
>

![alt github_release](../_media/github_release.png ':size=80%')



## 三、启动挖矿客户端

### 1、CLI启动方式

```shell
aleo-pool-client --dest=47.241.247.18:3030 run --miner-account testaccount001 --owner-name testserver001

--dest             #矿池节点地址
--miner-account    #挖矿账号
--owner-name       #主机名，默认为default
```



### 2、GUI启动方式

【敬请期待】



