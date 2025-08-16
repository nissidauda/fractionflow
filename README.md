FractionFlow Smart Contract

FractionFlow is a Clarity smart contract on the **Stacks blockchain** that enables **fractional ownership and transparent asset distribution**. It allows assets to be divided into fractions, distributed among multiple owners, and rewards shared proportionally — bringing liquidity and accessibility to traditionally indivisible assets.

---

Features
- **Fractionalized Assets** – Split assets into multiple fractions for shared ownership.  
- **Multiple Owners** – Allow several participants to hold fractional shares of an asset.  
- **Proportional Rewards** – Distribute revenue, profits, or benefits proportionally to fraction holders.  
- **Ownership Transfers** – Enable secure transfer of fractional ownership.  
- **On-chain Transparency** – Maintain immutable records of asset creation, ownership, and distribution.  

---

## ⚙️ Smart Contract Functions
- `create-asset` → Initialize a new fractionalized asset with a defined supply.  
- `transfer-fraction` → Transfer fractional ownership between users.  
- `distribute-rewards` → Distribute rewards proportionally to asset fraction holders.  
- `get-owner-share` → Query an owner’s current fractional share.  

---

Getting Started

Prerequisites
- [Clarinet](https://github.com/hirosystems/clarinet) (for testing and local development)  
- Stacks Blockchain Wallet (for deploying to mainnet/testnet)  

Installation
Clone the repository:
```bash
git clone https://github.com/your-username/fractionflow.git
cd fractionflow

clarinet test

clarinet deploy --testnet


