# ALEO Testnet

## Supporting Device

Opeartion System：Window、Linux

GPU：Nvidia Series



## Mining Pool URL

ws://aleo.zkrush.com:3030

wss://aleo.zkrush:3333



## 1.Add Mininng Account

1.1.Please refer to  [Add Mining Account](/en/_document/miner_account?=Add Mining Account)



## 2.Install Mining Client

 2.1.Download Address: https://github.com/zkrush/aleo-pool-client/releases

> ***Choose the version suitable for your opeartion system***
>
> ***aleo-pool-cllient is a mining program developed by ZKRush,optimized for GPU/CPU mining***

![alt github_release](../_media/github_release.png ':size=50%')



## 3、Start Mining Client

### 3.1、CLI Startup Method

```shell
# CPU Mining
./aleo-pool-client --dest=ws://aleo.zkrush.com:3030 run --miner-account=zkrush001 --owner-name=server001
```

```shell
# GPU Mining
FORCE_GPU_MINER=1 CUDA_VISIBLE_DEVICES=0 ./aleo-pool-client --dest=ws://aleo.zkrush.com:3030 run --miner-account=zkrush001 --owner-name=server001
```

**environment:**

FORCE_GPU_MINER=1 #Specify 1 for using GPU,default is 0

CUDA_VISIBLE_DEVICES=0 #Specify a GPU to run,start with GPU0,single process for the single GPU card

**option:**

--dest=ws://aleo.zkrush.com:3030 #Mining Pool URL

--miner-account=zkrush001 #Your Mining Account

--owner-name=server001 #Your Server Name,default is 'default'



### 3.2、GUI Startup Method

[Comming Soon]



