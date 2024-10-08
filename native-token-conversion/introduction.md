---
description: What is the conversion and how does it work?
---

# 💡 Introduction

## Daily's Native Token Conversion is COMPLETE!&#x20;

Daily's native token conversion was completed on April 3, 2023.&#x20;

* [Official announcement](https://twitter.com/daily\_project/status/1643946667723436033?s=20)
* [Genesis PBFT block](https://mainnet.explorer.dailycrypto.me/pbft/0)

If you held DLY tokens on ETH, they have been mirrored over to Daily's mainnet. Please [set up a wallet](../wallet/) to access your tokens!&#x20;



## What is the Native Token Conversion?&#x20;

Prior to the conversion on April 3, 2023, the Daily token used to be an [ERC-20 contract](https://etherscan.io/address/0xf001937650bb4f62b57521824b2c20f5b91bea05) residing on the Ethereum blockchain. The conversion converts the ERC-20 tokens into the native tokens residing on the Daily blockchain.



## How the Conversion Works - Technically Speaking

Technically, the conversion is pretty simple: balances on the ERC-20 will be mirrored over to Daily's mainnet.&#x20;

The process must be done in coordination with the exchanges that the DLY token is currently listed on, since otherwise all deposits and withdrawals will be disabled on these exchanges.&#x20;

Here's a quick overview of the mechanics of the conversion,&#x20;

1. Coordinate with the exchanges on a specific date & time when the conversion will take place&#x20;
2. Disable the ERC-20 contract on Ethereum
3. Record the exact ETH block where the contract has been disabled, this is the cutoff block height&#x20;
4. Mirror the ERC-20 and staking contract balances at the cutoff block height&#x20;
5. All staked tokens will be returned to the stakers' wallets on Mainnet, a re-delegation process must take place after the conversion
6. 20% of 10bn tokens will be taken from the deployer address into a new Foundation delegation address, which will be delegating to dev-operated nodes on the mainnet - meant to help bootstrap the mainnet (see [section 5.2 of the Whitepaper](https://docs.dailycrypto.me/tech-whitepaper/economic-model#5.2-token-distribution))
7. A tiny amount of tokens (10 tokens) will be taken from the deployer address into a new faucet address, which will be used to generate minimal transactions traffic on the mainnet - it's not a technical requirement, but a cosmetic one&#x20;
8. New community site will be deployed&#x20;
9. Place these resulting balances inside the genesis block of the Mainnet&#x20;
10. Reset the Mainnet with the updated genesis block&#x20;
11. Deploy updated network statistics endpoints
12. Deploy community site claims contract&#x20;
13. Notify Mainnet validators to reset their nodes to the new version&#x20;

###

## Where we are in the conversion process

You can [track the status here](conversion-status.md).&#x20;
