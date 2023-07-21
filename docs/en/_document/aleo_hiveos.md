# ZKRush ALEO on HiveOS

## 1. Create Wallets

![hive_create_account](../_media/hive_create_account.png ':size=100%')

```shell
1. Click [Wallets]
2. Click [Add Wallet]
```

![hive_create_account2](../_media/hive_create_account2.png ':size=50%')

```shell
1. Choose [ALEO] in Coin
2. Input the mining account you created on ZKRush in [Address]
3. Click [Create]
```

⚠️If you didn't create mining account ever, Please refer to  [Add Mining Account](/en/_document/miner_account?id=add-mining-account)



## 2. Create Flight Sheets

```shell
1. Click [Flight Sheets]
2. Click [Create Flight Sheet]
```

![hive_create_flight2](../_media/hive_create_flight2.png ':size=100%')
```shell
1. Choose [ALEO] in Coin
2. Choose the wallet you just created in step 1
3. Choose [Configure in miner] in [Pool]
4. Choose [Custom] in [Miner]
5. Click [Setup Miner Config]
```

![hive_create_custom](../_media/hive_create_custom.png ':size=50%')

```shell
1. Input [https://github.com/zkrush/aleo-pool-client/releases/download/v1.3-Beta/aleo-pool-prover-hiveos.tar.gz]
2. Input [%WAL%.%WORKER_NAME%] into [Wallet and worker template]
3. Input [https://aleo.zkrush.com:3334] into [Pool URL]
4. Click [Apply Changes]
5、Click [Create Flight Sheet]
```

⚠️Please follow the official announcement of ZKRush for the latest installation URL



## 3. Apply Flight Sheet

![hive_apply_flight](../_media/hive_apply_flight.png ':size=75%')

```shell
1. Click [Workers]
2. Choose [Workers]
3. Click [Select Flight Sheet] on the Navigation Bar
4. Choose [Flight Sheet] you just created in Step 2
```

![hive_apply_flight2](../_media/hive_apply_flight2.png ':size=50%')
```shell
1、Click [Apply]
```

⚠️Worker running automatically after applying the Flight sheet

## 4. Check Worker Status

![hive_miner_status](../_media/hive_miner_status.png ':size=100%')
