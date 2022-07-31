# Worker Hashrate

#### Worker Status Checkup

Visit the navigation bar at the top of the website and click on Worker to enter the **worker management** page.

In the worker management page, you can view the hashrate of all the workers under your current mining account.

![worker_mngm](../_media/worker_mngm.png ':size=100%')

**Explanations to Terms Displayed on this Page:**

- **All**: All workers under your current mining account.
- **Online Workers**: Properly functioning workers under your current mining account.
- **Offline Workers**: Workers fail to submit shares within an hour under your current mining account.
- **Worker Name**: The host name configured by the mining program, initally set as ‘default’. If it is not configured or set up as the same host name, the data of multiple workers will be combined for statistics.
- **Hashrate/15min**: The average hashrate in the last 15 minutes. Some big flunctuations may occur if workers are running less than 15 minutes.
- **Hashrate/24h**: The average hashrate in the last 24 hours. Some big flunctuations may occur if workers are running less than 24 hours
- **Local Hashrate**: The average hashrate in the last 15 minutes. Some big flunctuations may occur if workers are running less than 15 minutes. (Please note that local hashrate contains valid and invalid shares submitted.)
- **Latency**: The time interval between the action made and action accepted in last 15 minutes, mainly affected by network delay and computation rate.
- **Rejection**:Within 15 minutes, the illegal computing power ratio submitted by miners is invalid computing power.
- **Export**: Export worker running status locally as needed.
- **Group**: The group of current workers. For more details, please refer to [Worker Group](/en/_document/miner_group)。

 > ***ZKRush uses H/s as the computing power unit when calculating aleo computing power, that is, the number of hashes per second; if you need the data per minute, please multiply the result by 60***



#### Run Chart of Worker Hashrate

Select a specific worker to view a run chart of its hashrate in 24 hours.

![alt worker_chart](../_media/worker_chart.png ':size=50%')