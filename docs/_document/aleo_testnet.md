# ALEO測試網挖礦教程

## 支持設備

操作系統：Window、Linux

GPU：N卡



## 礦池節點地址

wss://aleo.zkrush.com:3333



## 1、添加挖礦賬號

1.1、參考文檔 [添加挖礦賬號](/_document/miner_account?id=添加挖礦賬號)



## 2、獲取挖礦客戶端

 2.1、客戶端下載地址: https://github.com/zkrush/aleo-pool-client/releases

> ***選擇適合您操作系統的版本***
>
> ***aleo-pool-cllient是ZKRush自研發的aleo挖礦程序，針對GPU/CPU挖礦都進行了大量優化***

![alt github_release](../_media/github_release.png ':size=50%')



## 3、啟動挖礦客戶端

### 3.1、CLI啟動方式

```shell
# CPU挖礦
./aleo-pool-client --dest=wss://aleo.zkrush.com:3333 run --miner-account=zkrush001 --owner-name=server001
```



```shell
# GPU挖礦
FORCE_GPU_MINER=1 CUDA_VISIBLE_DEVICES=0 ./aleo-pool-client --dest=wss://aleo.zkrush.com:3333 run --miner-account=zkrush001 --owner-name=server001
```

**環境變量：**

FORCE_GPU_MINER #指定1為開啟GPU，默認為0

CUDA_VISIBLE_DEVICES #指定GPU卡運行，從0開始；多卡主機分別啟動多個進程

**啟動參數：**

--dest #礦池節點地址

--miner-account #挖礦賬號

--owner-name #主機名，默認為default



### 3.2、GUI啟動方式

【敬請期待】



## 4、代理節點（可選项）

### 4.1 aleo-pool-proxy

> ***如有您有2台及以上的挖礦設備，我們強烈建議您在本地啟動aleo-pool-proxy作為代理節點。***

```shell
# 代理節點
./aleo-pool-proxy --dest="wss://aleo.zkrush.com:3333" --listen=0.0.0.0:4040 --miner-account=zkrush001 --owner-name=server001
```

**啟動參數：**

--listen #代理節點監聽端口，默認為0.0.0.0:4040

--dest #礦池節點地址

--miner-account #挖礦賬號

--owner-name #主機名，默認為default



### 4.2 aleo-pool-client

> 使用代理節點後，aleo-pool-client程序在啟動時，只需要指定代理節點的IP和Port即可，例如：

```shell
./aleo-pool-client --proxy="<代理節點IP地址>:4040"
```

















