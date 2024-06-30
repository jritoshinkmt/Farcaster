# 📟 Farcaster Hubble Node
_[Hubble](https://github.com/farcasterxyz/hub-monorepo) is an implementation of the [Farcaster Hub Protocol](https://github.com/farcasterxyz/protocol), written in [TypeScript](https://www.typescriptlang.org/) and [Rust](https://www.rust-lang.org/)._

![image](https://github.com/jritoshinkmt/Farcaster/assets/80070027/39fd1c2e-455e-4a20-8ca5-25684fa37624)

<br>

## Requirements
Hubble can be set up in less than 30 minutes. You'll need a machine that has:
<table>
  <tr>
    <td>Memory</td>
    <td>16 GB of RAM</td>
  </tr>
  <tr>
    <td>CPU</td>
    <td>4 CPU cores or vCPUs</td>
  </tr>
  <tr>
    <td>Disk</td>
    <td>40 GB of free storage</td>
  </tr>
</table>

<br>

## Obtaining Your Warpcast FID
![image](https://github.com/jritoshinkmt/Farcaster/assets/80070027/16e61492-05ae-48a0-a16d-370809bc2cd7)

• Visit https://warpcast.com
<br>
• Login or create an account (if you don't have one)
<br>
• Navigate to your profile, select About, and note down your FID

<br>

## Setting Up an API RPC
<p align="center">
  <img src="https://github.com/jritoshinkmt/Farcaster/assets/80070027/0c0988ad-715a-49af-a9be-265ac417959a" alt="all-endpoints" width="180"/>
  <img src="https://github.com/jritoshinkmt/Farcaster/assets/80070027/bc22c6d8-47b1-44e8-9003-5ca2e72bf31a" alt="active-endpoints" width="270"/>
</p>

• Visit https://app.infura.io
<br>
• Login or create an account
<br>
• Select **My First Key**
<br>
• Check Endpoints for **Ethereum** and **Optimism**
<br>
• Click on **Active Endpoints** to view your RPC URL, which you will need later

<br>

## ➤ Getting Started Farcaster Hubble VPS
**Update & Upgrade Packages**
```
sudo apt update -y
```
```
sudo apt upgrade -y
```
<br>

**Install Curl**
```
sudo apt-get install curl -y
```
<br>

**Install Screen**
```
sudo apt install screen -y
```
<br>

**Create a Screen session**
```
screen -S farcaster
```

<br>

## ➤ Run the installation script:
```
curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash
```
> [!NOTE]
> Wait for the script to complete, then enter the following configuration details in order:
> 1.	**RPC Ethereum Mainnet**
> 2.	**RPC OP Mainnet**
> 3.	**FID**
>
> 
> If you successfully run the script and see the specified image on your VPS (as shown below), your node is operational.
![image](https://github.com/jritoshinkmt/Farcaster/assets/80070027/77d49d4c-39b5-423d-b0cd-d5a0b684dd53)

<br>

For a safe exit, press **CTRL** + **A** + **D** to detach from the screen session. To reconnect to the running Farcaster node, log back into your VPS and run:
```
screen -r farcaster
```

<br>

> [!IMPORTANT]
> After completing all steps, you can check the node's status on your browser:
> - Navigate to `http://<YourServerIP>:3000`
> 
> _It may take a few hours to verify if the node has launched successfully._

---

