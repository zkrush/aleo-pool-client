# ALEO Testnet

## Supporting Device

Operation System: Ubuntu 20.04

GPU: Nvidia Series



## Mining Pool URL

https://aleo.zkrush.com:3333



## 1. Add Mining Account

1.1.Please refer to  [Add Mining Account](/en/_document/miner_account?id=add-mining-account)



## 2. Install Mining Client

 2.1.Download Address: https://github.com/zkrush/aleo-pool-client/releases

> ***aleo-pool-prover is a mining program developed by ZKRush, optimized for GPU mining***

![alt github_release](../_media/github_release.png ':size=50%')



## 3. Start Mining Client

```shell
./aleo-pool-prover grpc --dest https://aleo.zkrush.com:3333 --account zkrush001 --machine-name test01
```



**startup options:**

--dest #Mining Pool URL

--account #Your Mining Account

--owner-name #Your Server Name













