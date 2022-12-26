## DeFi Dapp

Defi dapp using aave

In this dapp, we 
1. Deposit Collateral : ETH / WETH 
2. Borrow another asset: DAI
3. Repay the DAI

The AAVE Protocol treats everything as an ERC20 Token, so instead of using ETH (which is not a ERC20 Standard) we are using WETH (Wrap ETH). Instead of using Mock contracts we Fork the mainnet using hardhat and MAINNET RPC URL. 

First of all we apprrove the ERC20 to interact with AAVE Protocol. then write
Deposit Collateral function
Borrow anther asser: borrow DAI by collateraling WETH
Rapay DAI function
