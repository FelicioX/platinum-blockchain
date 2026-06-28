# Platinum Blockchain

Platinum (PLAT) is an open-source cryptocurrency built on a hybrid Proof of Stake (PoS) and Masternode consensus model. Inspired by the Bitcoin, Dash and PIVX codebases, Platinum was designed to provide a secure, decentralized and energy-efficient blockchain suitable for everyday digital payments.

Unlike traditional Proof of Work cryptocurrencies, Platinum utilizes an energy-efficient staking protocol that significantly reduces power consumption while maintaining network security through decentralized consensus and masternode infrastructure.

---

## Desktop Wallet

The image below shows the Platinum Core desktop wallet.

<p align="center">
        <img width="722" height="374" alt="image" src="https://github.com/user-attachments/assets/9d92d2ea-8302-4909-9e42-67d64cf05643" />
      </p>

---

# Features

- Hybrid Proof of Stake consensus
- Masternode network
- SwiftTX instant transactions
- Desktop Wallet (Qt)
- Wallet encryption
- Peer-to-peer blockchain network
- JSON-RPC support
- Blockchain synchronization
- Coin Control
- Staking support
- Transaction history
- Address book
- Wallet backup and recovery

---

# Coin Specifications

| Parameter | Value |
|-----------|-------|
| Coin Name | Dash Platinum |
| Ticker | DASHP |
| Algorithm | X11 |
| Consensus | Proof of Stake + Masternodes |
| Block Time | 180 Seconds |
| Maturity | 180 Minutes |
| Masternode Collateral | 3,000 DASHP |
| Masternode Reward | 80% |
| PoS Reward | 20% |
| Premine | 2% (394,000 DASHP) |
| Maximum Supply | 19,700,000 DASHP |
| Estimated Emission Period | Over 100 Years |
| Genesis Date | February 3, 2019 |

---

# Reward Schedule

| Block Height | Reward |
|--------------|--------|
| 4 – 14,399 | 1.10 DASHP |
| 14,400 – 28,799 | 1.70 DASHP |
| 28,800 – 43,199 | 2.60 DASHP |
| 43,200 – 57,599 | 2.90 DASHP |
| 57,600 – 172,799 | 5.10 DASHP |
| 172,800 – 345,599 | 4.59 DASHP |
| 345,600 – 518,399 | 4.05 DASHP |
| 518,400 – 604,799 | 3.64 DASHP |
| 604,800+ | 3.28 DASHP |

---

# Consensus

The Platinum blockchain uses a hybrid consensus model based on:

- Proof of Stake (PoS)
- Masternodes
- SwiftTX instant transaction system

Each Masternode requires **3,000 DASHP** as collateral and receives **80%** of the block reward, while staking wallets receive the remaining **20%**.

---

# Build Dependencies

The project is based on the Bitcoin, Dash and PIVX codebases and uses the standard cryptocurrency development stack.

Typical dependencies include:

- C++
- Qt Framework
- Berkeley DB
- Boost
- OpenSSL
- MiniUPnPc
- LevelDB
- Protobuf

---

# Network Features

- Decentralized blockchain
- Peer-to-peer networking
- Wallet encryption
- Masternode support
- SwiftTX
- JSON-RPC interface
- Blockchain synchronization
- Staking
- Coin Control

---

# Repository Structure

```
src/            Blockchain source code
doc/            Documentation
depends/        Build dependencies
share/          Shared resources
contrib/        Development utilities
```

---

# Build

```bash
git clone https://github.com/FelicioX/platinum-blockchain.git

cd platinum-blockchain

mkdir build

cd build

cmake ..

make -j$(nproc)
```

---

# Historical Information

- Blockchain launch date: **February 3, 2019**
- Maximum supply: **19,700,000 DASHP**
- Initial premine: **2%**
- Estimated emission period: **More than 100 years**
- Approximately **2,808,504 DASHP** emitted during the first four years.

---

# Contact

Project contact:

**dashpnew@gmail.com**

---

# License

Distributed under the MIT License.
