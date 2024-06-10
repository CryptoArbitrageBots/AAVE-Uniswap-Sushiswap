# AAVE-Uniswap-Sushiswap
Aave Flash Loan Arbitrage with Uniswap,Sushiswap.

Project description. 

Aave Flashloan Arbitrage on Uniswap & Sushiswap. 

Flash Loan : Aave
Blockchain : Ethereum.
Language   : Solidity,
Tools      : Brownie,OpenZeppelin,Ganache. 
AMMs       : Uniswap,SushiSwap  

Setup:
1. Install Brownie,Ganache. 
2.Setup ENV vars.
3. MetaMask.
4. SEPOLIA ETH from SEPOLIA Faucet.
5. Program.
       flashloan()
       getPrice()
       comparePrice
       checkIfArbitrageIsProfitab()
       makeArbitrage()
       if (uniswapPrice > sushiswapPrice) buy ETH on sushiswap sell in uniswap for DAI
       if (uniswapPrice < sushiswapPrice) buy ETH on Uniswap Sell on sushiswap for DAI.
