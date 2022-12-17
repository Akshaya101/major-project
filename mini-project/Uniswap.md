## Uniswap
- Application that allows the exchange of ERC 20 tokens
- Very easy user interface
- You are in control of your assets the entire time
- Open source
- Uniswap does not charge any fee for exchange
- Factors depending on the swap or exchange
    - Liquidity Provider fees
        - liquidity providers have to deposit pre determined ETH in the liquidity pool 
        - In return for providing liquidity to the protocol, they earn fees from trades in their pool
    - Slippage
        - amount of change between placing of order and it being executed
    - Price impact
        - difference between market price and estimated price due to trade sizee
    - Amount of time you want trade to remain open

### Liquidity Pools
- they are a mech through which you make profit
- they are a place where all tokes sit
- you have to deposit equal dollar amount of tokens you want to exchage, say you want to get into DAI-ETH pool you have to have equal dollar value of the same amount

#### V2 (Ignore this!)
- [defi faced flash loans (talk about the scam)](https://www.coindesk.com/tech/2020/02/19/everything-you-ever-wanted-to-know-about-the-defi-flash-loan-attack/)

## Uniswap 
- It is an automated liquidity protocol powered by constant product formula implemented in a system of non upgradeable smart contracts on ethereum blockchain.
- It removes the need for trusted intermediaries, prioritizes blockchain, and security. 
- Uniswap is opensource, meaning you can look into the code behind how it's specific features work.

**Liquidity Providers**
- Anyone can become a liquidity provider (LP) for a pool by depositing an equivalent value of each underlying token in return for pool tokens. 
(read while working of application)[https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works]

### Contracts involved in the Uniswap Protocol

**Core**
Smart contracts that are considered foundational, and are essential for Uniswap to exist. Upgrading to a new version of core would require deploying an entirely new set of smart contracts on Ethereum and would be considered a new version of the Uniswap Protocol.

**Periphery**
External smart contracts that are useful, but not required for Uniswap to exist. New periphery contracts can always be deployed without migrating liquidity.

