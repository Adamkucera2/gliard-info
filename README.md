# Gliard

Crypto payments for Discord communities. Gliard lets members send and request supported tokens using their own wallets, with payment status checked against the blockchain.

- Website: [gliard.com](https://gliard.com)
- Web signer: [pay.gliard.com](https://pay.gliard.com)
- Add the bot and find the current setup instructions on [the Gliard website](https://gliard.com)
- [Terms of service](https://pay.gliard.com/terms) · [Privacy policy](https://pay.gliard.com/privacy)

## What Gliard does

- `/send` and `/request` help Discord members pay each other.
- Server administrators can register existing community tokens for payment commands.
- Payments are checked on-chain before Gliard marks a request as complete.

## Supported networks

Gliard supports Solana, Base, Arbitrum, Ethereum, and Polygon. Elysium is supported as a testnet for HYPE and registered community tokens. Available tokens depend on the network and each Discord community's configuration.

## How payments work

1. A member links a public wallet address to their Discord account.
2. They create a payment request or send intent in Discord.
3. The payer reviews the transaction and signs it with their own wallet.
4. Funds move directly from the payer's wallet to the recipient's wallet. Gliard does not hold user funds.
5. Gliard checks the transaction on-chain and updates the payment status.

Gliard does not need a wallet seed phrase or private key. Never share either with a person, bot, or website.

## About this repository

This is a public information repository for Gliard. It contains product information only; the application source code and deployment configuration are not published here. This repository does not grant a license to Gliard's application source code.

Product and network availability can change. Refer to [gliard.com](https://gliard.com) for current information.
