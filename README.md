# Bitcoin Limited Edition (BTCLE)

Official repository for BTCLE token metadata, wallet asset listing files, and public project documentation.

## Official Token Information

- Name: Bitcoin Limited Edition
- Symbol: BTCLE
- Network: BNB Smart Chain (BEP20)
- Contract: `0x9d2144328e1d618F54Cd38540F5eE50671f6A208`
- Decimals: `18`
- Max Supply: `210,000 BTCLE`
- Circulating Supply: `21,000 BTCLE`
- Locked and Vested: `189,000 BTCLE` (10 years via UNCX)

## Links

- Website: [https://bitcoin-limitededition.com](https://bitcoin-limitededition.com)
- Whitepaper: [https://bitcoin-limitededition.com/?page=whitepaper](https://bitcoin-limitededition.com/?page=whitepaper)
- BscScan Token: [https://bscscan.com/token/0x9d2144328e1d618F54Cd38540F5eE50671f6A208](https://bscscan.com/token/0x9d2144328e1d618F54Cd38540F5eE50671f6A208)
- BscScan Source Code: [https://bscscan.com/address/0x9d2144328e1d618F54Cd38540F5eE50671f6A208#code](https://bscscan.com/address/0x9d2144328e1d618F54Cd38540F5eE50671f6A208#code)
- CoinMarketCap: [https://coinmarketcap.com/currencies/bitcoin-limited-edition/](https://coinmarketcap.com/currencies/bitcoin-limited-edition/)
- CoinGecko: [https://www.coingecko.com/en/coins/bitcoin-limited-edition/](https://www.coingecko.com/en/coins/bitcoin-limited-edition/)
- Telegram: [https://t.me/BTCLE_Official](https://t.me/BTCLE_Official)
- X (Twitter): [https://x.com/bitcoinbtcle](https://x.com/bitcoinbtcle)

## Repository Contents

- `info.json`: Trust Wallet / asset repository standard metadata.
- `tokenlist.json`: Standard token-list format for wallet and dApp discovery.
- `SECURITY.md`: Security and verification policy.
- `docs/TOKENOMICS.md`: Tokenomics and vesting summary.
- `docs/TRUSTWALLET_PR.md`: Step-by-step Trust Wallet PR instructions.
- `docs/TOKEN_LISTS.md`: MetaMask and token-list submission instructions.
- `logo.png`: Project logo file (must follow exact technical rules).

## Repository Structure

```text
btcle-listing-repo/
├── .gitignore
├── README.md
├── SECURITY.md
├── info.json
├── logo.png
├── tokenlist.json
├── assets/
│   ├── README.md
│   ├── logo-source.svg
│   └── logo.png
└── docs/
    ├── TOKENOMICS.md
    ├── TOKEN_LISTS.md
    └── TRUSTWALLET_PR.md
```

## Logo Requirements

Use these exact specifications for Trust Wallet and token list submissions:

- File name: `logo.png` (lowercase only)
- Format: PNG
- Recommended size: `256 x 256` pixels
- Maximum size: `512 x 512` pixels
- Aspect ratio: `1:1`
- Maximum file size: `100 KB`
- Background: transparent outside the logo; design should stay visible on light and dark themes

## MetaMask Visibility (Token List)

MetaMask does not auto-read all tokens from BscScan. It relies on token lists and manual imports.

### Manual Add (works immediately)

In MetaMask:

1. Import token
2. Contract: `0x9d2144328e1d618F54Cd38540F5eE50671f6A208`
3. Symbol: `BTCLE`
4. Decimals: `18`

### Token List URL

After publishing this repository, this file can be used as a token list URL:

`https://raw.githubusercontent.com/BitcoinLimitedEdition1/btcle-listing-repo/main/tokenlist.json`

Users can import this token list URL in wallets/dApps that support custom token lists.

## Trust Wallet Global Logo Fix

To make the BTCLE logo appear for all new Trust Wallet users:

1. Submit token/logo through [https://assets.trustwallet.com](https://assets.trustwallet.com)
2. Use contract: `0x9d2144328e1d618F54Cd38540F5eE50671f6A208`
3. Upload `logo.png` and metadata from `info.json`
4. Complete pull request flow to `trustwallet/assets`
5. Pay processing fee when the bot requests it (500 TWT or 2.5 BNB)

Trust Wallet review and merge are manual and not guaranteed.

## Security and Listing Policy

- Contract source is already publicly verified on BscScan.
- This repository intentionally contains only public metadata, docs, and branding assets.
- Do not commit private keys, seed phrases, deployment secrets, or wallet access credentials.

## Disclaimer

This repository is for public token metadata and documentation. It is not financial advice.
# BTC-Limited-Edition
