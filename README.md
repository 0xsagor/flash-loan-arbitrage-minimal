# Flash Loan Arbitrage Minimal

This repository provides a high-quality boilerplate for interacting with Aave V3 Flash Loans. It uses a flat-file structure to keep logic transparent and accessible.

## How it Works
1. **Request:** The contract requests a specific amount of an asset from the Aave Pool.
2. **Execute:** The `executeOperation` function is triggered by the provider. You place your arbitrage logic (e.g., swapping on Uniswap vs. Sushiswap) inside this function.
3. **Repay:** The contract automatically calculates the premium (0.05%) and ensures the loan is repaid in the same transaction.



## Prerequisites
- Node.js and NPM
- An Alchemy or Infura API Key (for Mainnet Forking)
- Basic understanding of the Aave V3 Logic
