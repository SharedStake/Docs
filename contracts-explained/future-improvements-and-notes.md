# Future Improvements & Release Guide

### Future improvements

* Distributor: Non-continuous cumulative airdrops with updateable merkle root. This contract will be implemented from the current Airdrop contract and be used on to distribute Eth2 staking profits to the SharedStakers.
* Staking geysers will continue to be improved upon \(updatability, eliminating required migration ever three months, etc.\).

### Release guide

* Release vEth2Token.sol with your address for owner and minter
* Release Minter.sol using the vEth2 token address
* Call set minter on vEth2 to transfer the ownership to Minter address.
* In the case of contract upgrades, Minter has a setMinter feature to transfer the token supply to the new contract

### Notes

* Minter will not transfer non-staked Ether to the new contract!

