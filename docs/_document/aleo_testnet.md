# ALEO測試網挖礦教程

## 支持設備

操作系統：Ubuntu 20.04

GPU：N卡



## 礦池節點地址

https://aleo.zkrush.com:3333



## 1、添加挖礦賬號

1.1、參考文檔 [添加挖礦賬號](/_document/miner_account?id=添加挖礦賬號)



## 2、獲取挖礦客戶端

 2.1、客戶端下載地址: https://github.com/zkrush/aleo-pool-client/releases

> ***aleo-pool-prover是ZKRush自研發的aleo挖礦程序，針對GPU挖礦都進行了大量優化***

![alt github_release](../_media/github_release.png ':size=50%')



## 3、啟動挖礦客戶端

```shell
./aleo-pool-prover grpc --dest https://aleo.zkrush.com:3333 --account zkrush001 --machine-name test01
```



**啟動參數：**

--dest #礦池節點地址

--account #挖礦賬號

--machine-name #主機名







