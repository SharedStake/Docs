# 🔩 Staking to Eth2

The staking process is handled by a contract defined as a [Minter Contract](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) for [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1)token, which is a yield bearing equivalent of Eth2. This contracts are deployed to the main-net:

After users staked their Ether in the protocol, they can withdraw Eth by burning [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1) unlike the other protocols, where their tokens are immediately locked or need a notice period until claimed. This functionality decreases the risks and costs and increases the usability of the protocol. Shortly, no one will be forced to hold their [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1). 

{% page-ref page="../staking/notable-features/unstaking-your-ether-with-sharedstake.md" %}

After some period of time \(TBA\) or reaching a chosen limit of balance \(TBA\), the staking process will start. 

Here, the minter contract is paused to prevent any losses while creating the validators. Our automated bots will deploy multiple validators to the [Eth2.0 Deposit Contract](https://etherscan.io/address/0x00000000219ab540356cBB839Cbe05303d7705Fa). After this process, the [Minter Contract](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) will be unpaused and functioning again. 

\*\*\*\*[**Minter Contract**](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) **can be updated with SIPs which will be voted by DAO with SGT.**  


