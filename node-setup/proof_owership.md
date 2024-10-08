---
description: Guide for getting proof of ownership for node
---

# 📒 Node Proof of Owership

To find out your node's public address you can run the following command in a new terminal window while the node is running:

```bash
docker exec daily_compose_node_1 daily-sign sign --wallet /opt/daily_data/conf/wallet.json
```

{% hint style="info" %}
The node container's name could be different on different operating systems. For example, on Windows, it is `daily_compose-node-1`.&#x20;

To be sure what the name of the container is, execute `docker containers ls` to see a list of the containers running.&#x20;
{% endhint %}

You should see an output similar to the following:

```
0x1c26ec6c5679fbd270cbe0a1ed30894cfe7d1ae4909a81911af2d3e8fef7f4962187970dab6dda64e6a5c48bb2e833f1adb44eb2dc31ccffc00369f2c2b14a381c
```

This is the proof of ownership that you can use to register your node on our community site.
