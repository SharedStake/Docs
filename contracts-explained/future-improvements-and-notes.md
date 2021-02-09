# Future Improvements & Notes

### Future Improvements

* Distributor: Non-continuous cumulative airdrops with updateable merkle root. This contract will be implemented from the current Airdrop contract, to be used on distribution of eth2 staking profits to the stakers.
* Staking Geysers should be improved to have updatability, to eliminate the need for migration that will happen every 3 months.

### Release guide

* Release vEth2Token.sol with your address for owner and minter
* Release Minter.sol, using the vEth2 token address
* Call set minter on vEth2 to transfer the ownership to Minter address.
* In the case of contract upgrades, Minter has a setMinter to transfer the token supply to the new contract

### Notes

* Minter will not transfer non-staked Ether to the new contract!

