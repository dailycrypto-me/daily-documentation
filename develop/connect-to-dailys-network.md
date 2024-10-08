---
description: Talking to the Daily Network via RPC
---

# 🔗 Connecting to Daily

## Connecting to Daily's ETH-Compatible Network&#x20;

There are two ways to connect to Daily's network,

* Via dev-deployed RPC endpoints&#x20;
* Via your own mainnet / testnet nodes

Since Daily's network is almost 100% ETH-compatible, you can simply follow [Ethereum's JSON-RPC documentation](https://ethereum.org/en/developers/docs/apis/json-rpc/#usage-example).&#x20;

The ETH-compatibility with Ethereum also means that almost all tools from the Ethereum ecosystem work with Daily. You can use, for example, [Web3.js](https://web3js.org/), [ethers.js](https://docs.ethers.io/v5/) and [Web3.py](https://web3py.readthedocs.io/en/latest/) to connect to and interact with the Daily Network.

There are a few minor exceptions and quirks to Daily's ETH-compatibility, you can find them in our [full RPC specification](daily-rpc-specs.md).&#x20;



## Connect via RPC endpoints provided by the dev team&#x20;

You may use the RPC endpoints provided by Daily's core development team. Right now these are being provided as is and free of charge, this may change later of course with plenty of notice given to the community.&#x20;

* Mainnet: [https://rpc.mainnet.dailycrypto.me](https://rpc.mainnet.dailycrypto.me)
* Testnet: [https://rpc.testnet.dailycrypto.me/](https://rpc.testnet.dailycrypto.me/)&#x20;

More details on [Daily's network connections](../wallet/dailys-network-connection-details.md), including chain-ids etc.&#x20;



## Connect via your own Nodes

You could also set up your own nodes on the Mainnet or Testnet. This give you a lot of flexibility in working with your DApp.

If these nodes are being used primarily for RPC connections, they do NOT need to participate in consensus. Therefore there is no need to register them on the community site, or seek delegation for the mainnet nodes.&#x20;

Here are node setup instructions,&#x20;

* Setting up a [mainnet node](../become-a-validator/)&#x20;
* Setting up a [testnet node](../node-setup/testnet\_node\_setup/)&#x20;

The default RPC port on the Daily node is "7777". So if you're running this on your own node on the node's local machine, you'd send the RPC request to `localhost:7777`.&#x20;

