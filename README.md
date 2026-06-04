# shadowdrop
ShadowDrop lets you send SOL and USDC to anyone — no wallet address needed.
# 💚 ShadowDrop

> Send SOL & USDC anonymously via claim link or QR code. Built exclusively for Seeker on Solana.

![ShadowDrop](https://ochinimus.github.io/shadowdrop/banner.png)

---

## What is ShadowDrop?

ShadowDrop lets you send SOL and USDC to anyone — no wallet address needed. Create a drop, fund it, and share the claim link or QR code. The recipient claims it directly to their Seeker wallet in seconds.

Sender and recipient wallets are **never linked on-chain**. Complete privacy, every time.

---

## Features

- 🔒 **Anonymous transfers** — no on-chain link between sender and recipient
- ⚡ **Instant claims** — recipients claim in seconds, no setup required
- 💵 **SOL & USDC** — send native SOL or USDC stablecoin
- 👥 **Multi-recipient drops** — split one drop between multiple people
- 🔁 **Cancel anytime** — full refund before the drop is claimed
- 🔍 **On-chain verified** — every drop verifiable on Solscan
- 📋 **Transaction history** — track all your drops
- 🔐 **Biometric confirmation** — fingerprint/face ID before sending
- 👤 **Contacts integration** — share directly via SMS to contacts
- ⏳ **48h expiry countdown** — drops expire automatically

---

## How It Works

1. **Create a Drop** — choose SOL or USDC, enter amount, approve in Seeker wallet
2. **Share the Link** — copy the claim link or show the QR code
3. **Recipient Claims** — they open the link and receive funds instantly

---

## Fee Structure

| Amount | Fee |
|--------|-----|
| Under $100 | Free |
| $100 and above | 1% |

Network fee: ~0.000065 SOL (less than $0.01)

For USDC drops: ~0.004 SOL rent required (returned when claimed or cancelled)

---

## Tech Stack

- **React Native** 0.73.6 (Android)
- **Solana web3.js** — transaction building
- **Mobile Wallet Adapter** — Seeker wallet integration
- **Firebase Firestore** — drop records
- **SPL Token** — USDC transfers
- **TweetNaCl** — encryption

---

## Security

- Each drop uses a unique ephemeral keypair
- Private key is encoded in the claim link — only the link holder can claim
- No server holds funds — everything is on-chain
- Cancel function returns funds directly to sender's wallet

---

## Download

Available on the **Solana dApp Store** for Seeker phones.

🌐 [shadowdrop.app](https://ochinimus.github.io/shadowdrop)

---

## License

MIT

---

*Built for Seeker · Powered by Solana*
