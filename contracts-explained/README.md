---
description: 'Current SharedStake architecture, as deployed on mainnet'
---

# 🤖 Contracts Explained

The contracts pool users’ ETH, and automatically send 32 ETH batches into AWS-hosted ETH2 validators. Here is what is happening under the hood:

1. Users deposit ETH into a SharedStake smart contract through a deposit function on the SharedStake website.
2. This mints vETH2, a token representing the user's staked position.
3. The ETH supplied is held in a transparent smart contract until the predetermined threshold of 10 to 100 validators is met.
4. At this point, a SharedStake Core Dev creates the private keys and mnemonic via the command line, then deposits the ETH2 staking contract by calling a `deposit_to_eth2` function on the SharedStake contract.
5. This function transfers the ETH to the ETH2 staking contract by calling the deposit and passing the public key and additional required information.

This process allows holders to stake **any** amount of ether they want and pool infrastructure costs, maximizing their profits. ****

![](../.gitbook/assets/explained.jpg)

### V2 Planned Architecture

![](../.gitbook/assets/thefutureofsharedsteak2.jpg)

{% hint style="info" %}
**All of our contracts are open source and can be found on the SharedStake** [**Github**](%20https://github.com/SharedStake/Contracts)**.**
{% endhint %}

