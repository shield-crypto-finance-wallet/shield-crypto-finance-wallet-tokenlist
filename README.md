# shield-crypto-finance-wallet
Token list for the Shield Crypto Finance Wallet UI

## Overview
This repository contains the official token list for the Shield Crypto Finance Wallet UI. The token list provides metadata for tokens supported by the wallet interface across multiple blockchain networks.

## Complete Token List

The token list includes all tokens from the original JSON file:

**Ethereum Mainnet (Chain ID: 1)**
- USDT (Tether USD) - 0xdAC17F958D2ee523a2206206994597C13D831ec7
- USDC (USD Coin) - 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48
- DAI (Dai Stablecoin) - 0x6B175474E89094C44Da98b954EedeAC495271d0F
- WETH (Wrapped Ether) - 0xC02aaA39b223FE8D0A0E5C4F27eAD9083C756Cc2
- WBTC (Wrapped Bitcoin) - 0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599
- ETH (Ether) - 0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE

**BSC Mainnet (Chain ID: 56)**
- USDT (Tether USD) - 0x55d398326f99059fF775485246999027B3197955
- USDC (USD Coin) - 0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d
- WBNB (Wrapped BNB) - 0xbb4CdB9CBd36B01bD1cBaEBF2De08d9173bc095c
- BNB (Binance Coin) - 0x0000000000000000000000000000000000000000

**Polygon Mainnet (Chain ID: 137)**
- USDC (USD Coin) - 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174
- USDT (Tether USD) - 0xc2132D05D31c914a87C6611C10748AEb04B58e8F
- MATIC (Polygon) - 0x0000000000000000000000000000000000001010

**Avalanche C-Chain (Chain ID: 43114)**
- WAVAX (Wrapped AVAX) - 0xB31f66AA3C1e785363F0875A1B74E27b85FD66c7

**Optimism (Chain ID: 10)**
- OP (Optimism) - 0x4200000000000000000000000000000000000042

**Arbitrum (Chain ID: 42161)**
- ARB (Arbitrum) - 0x912CE59144191C1204E64559FE8253a0e49E6548

**Goerli Testnet (Chain ID: 5)**
- WETH (Wrapped Ether) - 0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6
- ETH (Ether) - 0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE
- USDT (Tether USD) - 0xdc31Ee1784292379Fbb2964b3B9C4124D8F89C60
- USDC (USD Coin) - 0xD87Ba7A50B2E7E660f678A895E4B72E7CB4CCd9C

**Sepolia Testnet (Chain ID: 11155111)**
- WETH (Wrapped Ether) - 0x8267cF9254734C6Eb452a7bb9AAF97B392258b21
- ETH (Ether) - 0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE
- USDT (Tether USD) - 0x7169D38820dfd117C3FA1f22a697dBA58d90BA06
- USDC (USD Coin) - 0x1c7D4B196Cb0C7B01d743Fbc6116a902379C7238

**BSC Testnet (Chain ID: 97)**
- BNB (Binance Coin) - 0x0000000000000000000000000000000000000000
- WBNB (Wrapped BNB) - 0xae13d989daC2f0dEbFf460aC112a837C89BAa7cd
- USDT (Tether USD) - 0x337610d27c682E347C9cD60BD4b3b107C9d34dDd
- USDC (USD Coin) - 0x64544969ed7EBf5f083679233325356EbE738930

**Mumbai Polygon Testnet (Chain ID: 80001)**
- MATIC (Polygon) - 0x0000000000000000000000000000000000001010
- USDC (USD Coin) - 0xA02f6adc7926efeBBd59Fd43A84f4E0c0c91e832
- USDT (Tether USD) - 0x3813e82e6f7098b9583FC0F33a962D02018B6803

**Arbitrum Goerli Testnet (Chain ID: 421613)**
- ARB (Arbitrum) - 0xEe01c0CD76354C383B8c7B4e65EA88D00B06f36f
- ETH (Ether) - 0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE
- USDC (USD Coin) - 0x8FB1E3fC51F3b789dED7557E680551d93Ea9d892

**Optimism Goerli Testnet (Chain ID: 420)**
- OP (Optimism) - 0x4200000000000000000000000000000000000042
- ETH (Ether) - 0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE
- USDC (USD Coin) - 0xe05606174bac4A6364B31bd0eCA4bf4dD368f8C6

**Avalanche Fuji Testnet (Chain ID: 43113)**
- WAVAX (Wrapped AVAX) - 0xd00ae08403B9bbb9124bB305C09058E32C39A48c
- AVAX (Avalanche) - 0x0000000000000000000000000000000000000000
- USDC (USD Coin) - 0x5425890298aed601595a70AB815c96711a31Bc65

## Usage

Import the token list from our GitHub repository:

```
https://raw.githubusercontent.com/shield-crypto-finance-wallet/shield-crypto-finance-wallet-tokenlist/main/tokenlist.json
```

## Structure

Each token contains:
- chainId: Network identifier
- address: Token contract address
- name: Full token name
- symbol: Token symbol
- decimals: Number of decimal places
- logoURI: Token logo URL

## Version

Current version: 1.0.1
Last updated: 2025-05-21

## License

MIT License

## Contact

For support, open an issue on this repository.
