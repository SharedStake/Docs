---
description: 'You have your vEth2, but what''s happening to your ether?'
---

# 🔩 Staking to Eth2

The staking process is handled by a contract defined as a [Minter Contract](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) for the [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1) token. This contract is deployed to the main-net.

After users stake their ether in the SharedStake protocol, they can withdraw Eth by burning [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1). This functionality decreases the risks & costs and increases the usability of the protocol.

{% page-ref page="../fundamentals/notable-features/unstaking-your-ether-with-sharedstake.md" %}

The staking process is triggered after a predetermined period of time or once a balance limit is reached. 

At that point, the minter contract is paused to prevent any losses while creating the validators. SharedStake deploys multiple validators to the [Eth2.0 Deposit Contract](https://etherscan.io/address/0x00000000219ab540356cBB839Cbe05303d7705Fa). After this process, the [Minter Contract](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) is unpaused and continues to accept Eth and mint vEth2 again. 

**The** [**Minter Contract**](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) **can be updated with SIPs and voted on by DAO members with SGT.**

