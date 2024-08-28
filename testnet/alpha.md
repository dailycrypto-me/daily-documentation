---
description: Daily Alpha Testnet
---



# Block Explorer

 Check out our alpha testnet via the [Daily Block Explorer](https://explorer.testnet.dailycrypto.me/).

![](../.gitbook/assets/image%20%281%29.png)

<br>

# Ethereum compatible JSON RPC interface

To connect to the Daily Alpha Testnet, use the following options:
1. https: https://rpc.testnet.dailycrypto.me
2. websocket: wss://ws.rpc.testnet.dailycrypto.me

<br>

# Creating a wallet

- [Daily Sandbox](https://sandbox.testnet.dailycrypto.me) - For the testnet, Daily provides a web-based wallet called the sandbox.  The sandbox wallet provides 10 addresses that can be used for sending/receiving DLY, contract deployment, and staking.
- [MetaMask](https://metamask.io/) - MetaMask browser extention also works with Daily Alpha Testnet. Just use custom RPC, and set the token name to DLY, and use the block explorer above.

<br>


# Using the Faucet

Daily testnet includes a faucet. The faucet will send small amount of testnet DLY every few seconds, to the last 5000 addresses that were added.


<br>

# Development

### Libraries

- Web3 - Because of the Ethereum-compatible RPC interface, most Ethereum libraries like Web3.js, Web3.py, Ethers.js, etc will work for sending and receiving DLY and interacting with contracts.
- [DailyJS](https://github.com/dailycrypto-me/daily-js) - To access custom RPC functionality using JavaScript, try DailyJS (based on Axios)
- [DailyPy](https://github.com/dailycrypto-me/daily-py) - To access custom RPC functionality using Python, try DailyPy