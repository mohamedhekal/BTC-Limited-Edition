# Trust Wallet PR Guide (BTCLE)

This process fixes the generic BEP20 icon issue globally for new Trust Wallet users.

## Official Target Repository

- [https://github.com/trustwallet/assets](https://github.com/trustwallet/assets)

## Required Files

In Trust Wallet repository, your token must be in this exact folder:

`blockchains/smartchain/assets/0x9d2144328e1d618F54Cd38540F5eE50671f6A208/`

Files inside:

- `info.json` (use this repository's `info.json`)
- `logo.png` (256x256, max 100 KB)

## Recommended Submission Method (Assets App)

1. Open [https://assets.trustwallet.com](https://assets.trustwallet.com)
2. Click **Log in with GitHub**
3. Enter contract `0x9d2144328e1d618F54Cd38540F5eE50671f6A208`
4. Upload `logo.png`
5. Copy data from `info.json`
6. Click **Check** to validate
7. Click **Create Pull Request**
8. Wait for `merge-fee-bot` comment in your PR
9. Pay the fee exactly as requested with correct memo:
   - `500 TWT` or `2.5 BNB`
10. Wait for maintainer review and merge

## Manual Method (GitHub Fork + PR)

1. Fork `trustwallet/assets`
2. Create branch `add-btcle-token`
3. Create folder:
   - `blockchains/smartchain/assets/0x9d2144328e1d618F54Cd38540F5eE50671f6A208/`
4. Add `info.json` and `logo.png`
5. Commit and open PR
6. Pay fee via bot instructions

## Important Notes

- File names must be lowercase: `info.json`, `logo.png`
- Contract folder name must use exact checksum address
- Fee is non-refundable and does not guarantee merge
- Trust Wallet guidelines mention activity thresholds; approval is still discretionary
