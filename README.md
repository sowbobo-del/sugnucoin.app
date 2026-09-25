# SUGNUCOIN.APP
### Celo-native stablecoins for Francophone Africa

**SUGNUCOIN** is a suite of decentralized stablecoins pegged 1:1 to West & Central African currencies, built on Celo for ultra-low fees (< $0.001) and mobile-first payments.

🌍 Website: https://sugnucoin.app
📧 Contact: support@sugnucoin.app
🔗 CeloScan: Verified by SCAPLabs

---

## 🪙 Tokens Deployed

| Token | Peg | Contract Address | CeloScan |
|-------|-----|------------------|----------|
| **cXOF** | 1 XOF (West African CFA) | `0xB673678595e50ff1C622535aC30Ba39B8bE7a321` | [View](https://celoscan.io/token/0xB673678595e50ff1C622535aC30Ba39B8bE7a321) |
| **cXAF** | 1 XAF (Central African CFA) | `0x97F8BaB8ad137BaB2fD4C30eBF9B815CcF187FC4` | [View](https://celoscan.io/token/0x97F8BaB8ad137BaB2fD4C30eBF9B815CcF187FC4) |
| **cGNF** | 1 GNF (Guinean Franc) | `0xCB9F94165443DA5586449dFF5D6b87F49f02F6e6` | [View](https://celoscan.io/token/0xCB9F94165443DA5586449dFF5D6b87F49f02F6e6) |
| **Treasury** | Multisig / Reserve | `0x682f1393e4bb836C6c7471041efC000D1b5C2b8C` | - |

- Standard: ERC-20 on Celo
- Minting: On-demand 1:1, no ICO / no private sale
- Decimals: 18
- Verified on CeloScan: Yes (SCAPLabs - support@sugnucoin.app)

## 💡 Why SugnuCoin?

1. **150M+ people** use XOF / XAF / GNF but have no stablecoin on-chain
2. Celo fees are 1000x cheaper than banks / Mobile Money
3. Built for remittances, merchants, DeFi

## 🏗️ Architecture

```
User deposits XOF/XAF/GNF (via partner) -> Treasury mints cXOF/cXAF/cGNF -> User receives on Celo -> Spend / Swap / DeFi
```

- Treasury `0x682f...2b8C` holds collateral logic
- Tokens are burnable & mintable by Treasury only

## 📄 CeloScan Verification

All tokens submitted for Token Info Update on CeloScan (logo, name, website). Pending approval 24-72h.

## 🚀 Quick Start

```bash
# Add cXOF to MetaMask (Celo Mainnet)
Contract: 0xB673678595e50ff1C622535aC30Ba39B8bE7a321
Symbol: cXOF
Decimals: 18
```

## 📂 Repo Structure

- `/contracts` - Solidity sources (ERC20)
- `/metadata` - token logos & celoscan submission json
- `/pitch` - Pitch deck & one-pager

## 📬 Contact

SCAPLabs - Fano, Italy / West Africa
support@sugnucoin.app
https://sugnucoin.app
