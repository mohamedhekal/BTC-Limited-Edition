# Token Lists Guide (MetaMask and dApps)

MetaMask token discovery depends heavily on token lists, not only block explorer metadata.

## 1) Immediate Fix: Use Your Own Token List

This repository provides `tokenlist.json`.

After pushing to GitHub, your list URL is:

`https://raw.githubusercontent.com/BitcoinLimitedEdition1/btcle-listing-repo/main/tokenlist.json`

Users can import this URL into compatible wallets/dApps.

## 2) Manual Add in MetaMask (Fallback)

Use this when token-list import is not available:

- Contract: `0x9d2144328e1d618F54Cd38540F5eE50671f6A208`
- Symbol: `BTCLE`
- Decimals: `18`

## 3) Submit to PancakeSwap Token List

Target repository:

- [https://github.com/pancakeswap/token-list](https://github.com/pancakeswap/token-list)

Suggested flow:

1. Fork repository
2. Add BTCLE metadata according to their list format
3. Use your hosted logo URL
4. Open PR and follow maintainer feedback

Note: Review and acceptance are at maintainer discretion.

## 4) Token List Validation

Before submission:

1. Ensure JSON is valid
2. Use checksummed contract address
3. Confirm `chainId` is `56` for BNB Smart Chain
4. Ensure logo URL is publicly accessible

## 5) Uniswap Token List Schema Reference

- [https://github.com/Uniswap/token-lists](https://github.com/Uniswap/token-lists)
- [https://uniswap.org/tokenlist.schema.json](https://uniswap.org/tokenlist.schema.json)
