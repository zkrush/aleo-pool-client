# 在HiveOS上運行ZKRuh ALEO程序

## 一、創建錢包

![hive_create_account](../_media/hive_create_account.png ':size=100%')

```shell
1、進入【錢包】頁面
2、點擊【添加錢包】
```

![hive_create_account2](../_media/hive_create_account2.png ':size=50%')

```shell
1、數字貨幣選擇【ALEO】
2、地址輸入您在ZKRush官網創建的挖礦賬號
3、點擊【創建】
```

⚠️如未創建過挖礦地址，參考文檔 [添加挖礦賬號](/_document/miner_account?id=添加挖礦賬號)

![show_account](../_media/show_account.png ':size=50%')



## 二、創建飛行表

![hive_create_flight](../_media/hive_create_flight.png ':size=75%')

```shell
1、進入【飛行表】界面
2、點擊【添加飛行表】
```

![hive_create_flight2](../_media/hive_create_flight2.png ':size=100%')
```shell
1、數字貨幣選擇【ALEO】
2、錢包選擇您剛才創建的錢包
3、礦池選擇【挖礦軟件配置】
4、挖礦軟件選擇【Custom】
5、點擊【設定挖礦軟件配置】
```

![hive_create_custom](../_media/hive_create_custom.png ':size=50%')

```shell
1、安裝鏈接輸入【https://github.com/zkrush/aleo-pool-client/releases/download/v1.2/zkrushminer-v1.2.tar.gz】
2、錢包與礦機模版輸入【%WAL%.%WORKER_NAME%】
3、礦池地址輸入【tcp://aleo.zkrush.com:3333】
4、點擊【應用更改】
```

⚠️最新安裝鏈接請關注ZKRush官方公告

![hive_create_flight3](../_media/hive_create_flight3.png ':size=75%')

```shell
1、點擊【創建飛行表】
```
## 三、應用飛行表

![hive_apply_flight](../_media/hive_apply_flight.png ':size=75%')

```shell
1、點擊【礦機】
2、勾選【礦機】
3、點擊導航欄【飛行表圖標】
4、選擇剛才創建的【飛行表】
```

![hive_apply_flight2](../_media/hive_apply_flight2.png ':size=50%')
```shell
1、點擊【應用】
```

⚠️飛行表應用完成後，礦機自動拉取軟件包並自動啟動

## 四、查看礦機挖礦數據

![hive_miner_status](../_media/hive_miner_status.png ':size=100%')
