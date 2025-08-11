# Basic Token Swap Contract

## 1. Project Title
**Basic Token Swap on Stacks Blockchain**

## 2. Project Description
This Clarity smart contract enables users to swap between two predefined SIP-010 fungible tokens at a fixed exchange rate.  
It contains only two functions:
- `swap-a-for-b`: Swap Token A for Token B
- `swap-b-for-a`: Swap Token B for Token A  

The contract ensures that both token transfers occur atomically — either both succeed or neither does.

## 3. Project Vision
The vision of this project is to provide a simple, minimal, and error-free token swap mechanism for the Stacks blockchain.  
By keeping the logic straightforward, it allows developers to quickly integrate basic token swaps into their decentralized applications.

## 4. Future Scope
- Implement dynamic exchange rates based on market data.
- Integrate with decentralized liquidity pools.
- Add swap fees and fee distribution to liquidity providers.
- Allow admin to update token addresses and rates.
- Support multiple token pairs in one contract.

## 5. Contract Address
`SP000000000000000000002Q6VF78.basic-token-swap`  
*(Replace with your deployed contract address after deployment)*
