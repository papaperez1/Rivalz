# Rivalz incentivized client setup using VPS
![image](https://github.com/user-attachments/assets/f5fc321e-aa02-4ed6-b067-8886d26ea956)


### Login to Dashboard

Dashboard link: https://rb.gy/wa633r
Cconnect with your EVM wallet (OKX recommended)
Connect twitter and claim social points.

### Min System Requirement

8 GB RAM, 4 cores (2.2 GHz), 50GB SSD, 1Mps internet speed

### Run the client

```
sudo su -
```
```
sudo apt update
sudo apt upgrade -y
```
```
curl -fsSL https://deb.nodesource.com/setup_22.x | bash -
```
```
apt install -y nodejs
```
```
apt install npm
```
```
apt install screen
```
```
npm i -g rivalz-node-cli
```
```
rivalz update-version
```
```
screen -R node1
```
```
rivalz run
```
put your EVM wallet address that you connected in dashboard. No need seedphrase or private key.
type ctrl+a+d from keyboard and close your VPS. It will run in background.
Go to https://rivalz.ai/dashboard/node-validate and check status

![image](https://github.com/user-attachments/assets/e962fcc4-3c99-4b3e-8b6a-e681124a8466)


