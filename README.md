# Shield Crypto Finance Wallet Token List

Token list for the Shield Crypto Finance Wallet UI.

## Overview  
This repository contains the official token list (JSON metadata and logos) for the Shield Crypto Finance Wallet UI across multiple blockchains.

---

## Token List by Network

### Ethereum Mainnet (chainId: 1)  
- **USDT** (Tether USD) – `0xdAC17F958D2ee523a2206206994597C13D831ec7`  
- **USDC** (USD Coin) – `0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48`  
- **DAI** (Dai Stablecoin) – `0x6B175474E89094C44Da98b954EedeAC495271d0F`  
- **WETH** (Wrapped Ether) – `0xC02aaA39b223FE8D0A0E5C4F27eAD9083C756Cc2`  
- **WBTC** (Wrapped Bitcoin) – `0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599`  
- **BTC** (Bitcoin) – `0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599`  
- **ETH** (Ether) – `0xEeeeeEeeeEeEeeEeEeEeeEEEeeeeEeeeeeeeEEeE`  

### BSC Mainnet (chainId: 56)  
- **USDT** – `0x55d398326f99059fF775485246999027B3197955`  
- **USDC** – `0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d`  
- **WBNB** – `0xbb4CdB9CBd36B01bD1cBaEBF2De08d9173bc095c`  
- **BNB** – `0x0000000000000000000000000000000000000000`  

*(…continue for Polygon, Avalanche, Optimism, Arbitrum, and all testnets as you have above…)*

---

## Usage

Fetch the token list JSON in your dApp:

```js
const url = 'https://raw.githubusercontent.com/shield-crypto-finance-wallet/shield-crypto-finance-wallet-tokenlist/main/tokenlist.json';
const { tokens } = await fetch(url).then(res => res.json());
