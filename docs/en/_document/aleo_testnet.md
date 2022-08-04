# ALEO Testnet

## Supporting Device

Operation System: Window、Linux

GPU: Nvidia Series



## Mining Pool URL

wss://aleo.zkrush:3333



## 1. Add Mining Account

1.1.Please refer to  [Add Mining Account](/en/_document/miner_account?=Add Mining Account)



## 2. Install Mining Client

 2.1.Download Address: https://github.com/zkrush/aleo-pool-client/releases

> ***Choose the version suitable for your operating system***
>
> ***aleo-pool-client is a mining program developed by ZKRush, optimized for GPU/CPU mining***

![alt github_release](../_media/github_release.png ':size=50%')



## 3. Start Mining Client

### 3.1. CLI Startup Method

```shell
# CPU Mining
./aleo-pool-client --dest=wss://aleo.zkrush.com:3333 run --miner-account=zkrush001 --owner-name=server001
```

```shell
# GPU Mining
FORCE_GPU_MINER=1 CUDA_VISIBLE_DEVICES=0 ./aleo-pool-client --dest=wss://aleo.zkrush.com:3333 run --miner-account=zkrush001 --owner-name=server001
```

**environment:**

FORCE_GPU_MINER #Specify 1 for using GPU,default is 0

CUDA_VISIBLE_DEVICES #Specify a GPU to run, start with GPU0, and single process for the single GPU card

**startup options:**

--dest #Mining Pool URL

--miner-account #Your Mining Account

--owner-name #Your Server Name, default is 'default'



### 3.2. GUI Startup Method

[Comming Soon]



## 4. Proxy Node(optional)

### 4.1 aleo-pool-proxy

> ***If you have 2 or more mining devices, we strongly suggest you start a aleo-pool-proxy as a proxy node.***

```shell
# 代理節點
./aleo-pool-proxy --dest="wss://aleo.zkrush.com:3333" --listen=0.0.0.0:4040 --miner-account=zkrush001 --owner-name=server001
```

**stratup options:**

--listen #Proxy Node listening IP & port, default is '0.0.0.0:4040'

--dest #Mining Pool URL

--miner-account #Your Mining Account

--owner-name #Your Server Name, default is 'default'



### 4.2 aleo-pool-client

> When you start a proxy node, you only need to specify the IP and Port of the proxy node when you start a aleo-pool-client, for example:

```shell
./aleo-pool-client --proxy="<Proxy Node IP>:4040"
```

















