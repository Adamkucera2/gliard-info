# Gliard

Crypto payments for Discord communities. Gliard helps members send and request supported tokens with their own wallets, while server administrators can enable existing community tokens.

- Website: [gliard.com](https://gliard.com)
- Web signer: [pay.gliard.com](https://pay.gliard.com)
- Add the bot and find setup instructions on [the Gliard website](https://gliard.com)
- [Terms of service](https://pay.gliard.com/terms) · [Privacy policy](https://pay.gliard.com/privacy)

## Features

- **Send and request payments:** Use `/send` to pay a Discord member or `/request` to create a payment request. Request notifications include a direct payment link.
- **Link and manage wallets:** Use `/walletset` to link a Solana or EVM address, `/walletview` to see linked addresses and live balances, and `/walletremove` to unlink an address.
- **Use community tokens:** Server administrators can use `/customtoken` to add, list, and remove existing SPL or ERC-20 tokens for their community. Gliard reads token details from the relevant network; it does not create or issue tokens.
- **Swap supported EVM tokens:** Use `/swap` to get a route through the LI.FI aggregator and review and sign the swap in your wallet. Elysium Testnet and Solana swaps are not supported.
- **Pay from desktop or mobile:** The web signer supports connected browser wallets. Payment pages can also show a QR payment option for compatible mobile wallets, using Solana Pay or EIP-681 where supported.
- **On-chain payment checks:** Gliard checks the transaction details on the relevant network before marking a payment as complete.

## Supported networks

Gliard supports payments on Solana, Base, Arbitrum, Ethereum, and Polygon. Elysium is available as a testnet for HYPE and registered community tokens. Swap availability is limited to supported EVM networks, tokens, and routes; it does not include Solana or Elysium Testnet.

Available tokens and wallet options depend on the network and each Discord community's configuration.

## Fees

Direct payments include a 0.5% platform fee. The payer reviews and signs the transaction with their wallet.

## How payments work

1. A member links a public wallet address to their Discord account.
2. They create a payment or request in Discord.
3. The payer reviews the transaction details and signs with their own wallet.
4. Funds move directly from the payer's wallet to the recipient's wallet. Gliard does not hold user funds.
5. Gliard checks the transaction on-chain and updates the payment status.

Gliard does not need a wallet seed phrase or private key. Never share either with a person, bot, or website.

## About this repository

This is a public information repository for Gliard. It contains product information only; the application source code and deployment configuration are not published here. This repository does not grant a license to Gliard's application source code.

Product and network availability can change. Refer to [gliard.com](https://gliard.com) for current information.
