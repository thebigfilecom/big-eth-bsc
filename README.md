## BIG-ETH, BIG-BSC

Contract for BIG on Ethereum as ERC20 and BIG on Binance Smart Chain as BEP20.
Deployed code is identical on both chains.
Compiled with optimizations on big.sol.
big_flat can be used for single source sol verification, just like its done on etherscan, bscscan.

BigFile (BIG)
440 mil total supply
8 decimals

```
npm i -g truffle-flattener
truffle-flattener big.sol > big_flat.sol
```