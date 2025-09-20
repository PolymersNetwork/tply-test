# TPLY Token (Testnet) — Polymers Governance & XP Test Token

**TPLY** is the **testnet version** of the Polymers ecosystem token, deployed on **Solana Devnet** as an SPL token.  

It simulates the full lifecycle of a **utility and governance asset** in a real-world Web3 finance platform — including minting, distribution, staking, burning, and metadata locking.

> ⚠️ **Testnet Use Only:** TPLY tokens have no monetary value and cannot be transferred to mainnet. Their purpose is **testing governance, tokenomics, and UX** ahead of the Polymers mainnet launch (TGE).

---

## 🔧 Token Details

| Property | Value |
|----------|-------|
| Token Name | Polymers Test Token |
| Symbol | TPLY |
| Decimals | 9 |
| Total Supply | 18,000,000,000 TPLY |
| Network | Solana Devnet |
| Token Type | SPL Token |
| Mint Address | *[Mint Address]* | Mainnet: PLYKdaCUgxTUw6rSjWbgSN97Qtecb6Fy6SazWf1tvAC

### 🪪 Add TPLY to Phantom Wallet
Phantom Wallet supports Solana Devnet and custom token additions.  
Works on both **mobile and desktop** via deep link.

---

## 📌 Testnet Use Cases

- 🗳️ Simulated governance via **Realms**
- 🎮 XP-to-token claim mechanics and **quests**
- 📈 Vesting stream simulations via **Streamflow**
- 🏆 Community **leaderboard & ranking experiments**
- 🧩 Integration with **Telegram MiniApp** & **Matrix messenger**

---

## 🔐 Token Lifecycle: Testnet Simulation

The TPLY token has gone through all typical lifecycle stages of production-grade Web3 assets:

| Stage | Status |
|-------|-------|
| Minting | ✅ Completed (full supply issued) |
| Mint Authority | 🔒 Revoked permanently |
| Burn Capability | ✅ Available via CLI |
| Metadata Hosting | ✅ Migrated to IPFS |
| Update Authority | 🔒 Revoked (metadata locked) |

---

## 🧰 Components & Documentation

| File | Description |
|------|------------|
| `devnet/mint-info.txt` | Token mint ID and deployment data |
| `airdrop-script.sh` | CLI-based airdrop simulation |
| `tply-metadata.json` | IPFS-compatible metadata |
| `vesting-plans.md` | Vesting setup using Streamflow |
| `realms.md` | Governance instructions for Realms |
| `burn.md` | Token burn documentation |
| `mint-disabled.md` | Disabling minting authority |
| `lock-metadata.md` | Locking metadata permanently |
| `update-ipfs-uri.md` | Updating URI to IPFS-hosted metadata |

---

## 🧪 Developer Scripts

| Script | Function |
|--------|---------|
| `create-token.ts` | Mint the TPLY token on Devnet |
| `burn.ts` | Burn TPLY tokens from associated wallet |
| `disable-mint.ts` | Permanently revoke mint authority |
| `lock-metadata.ts` | Lock metadata (`updateAuthority = null`) |
| `update-ipfs-uri.ts` | Update token metadata URI to IPFS |
| `add-metadata.ts` | Create Metaplex metadata account |
| `update-metadata.ts` | General metadata updater |

---

## ⚠️ Disclaimer

This repository is **strictly for testnet development**.  
TPLY tokens **have no monetary value** and are **not transferable** to mainnet.  
They exist solely to **validate tokenomics, integrations, and UX** ahead of the Polymers PLY TGE.

---

Polymers — A next-gen **Web3 Recycling, ESG, e-waste management, and communication platform**.
