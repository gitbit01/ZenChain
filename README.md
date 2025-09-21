# ZenChain
ZenChain — Play, Learn, Earn lets users connect a wallet, view Zen Token (ZTC) balance, and spin a mini-game to win or lose ZTC. Includes a faucet for new users, real-time token reads, and a polished UI showcasing fun, interactive web3 gameplay and blockchain mechanics.

# ZenChain — Play, Learn, Earn (Demo)

A polished web3 demo showcasing **ZenChain's token (ZTC)**, a **faucet onboarding system**, and a **mini-game spinner** to illustrate how users can interact with blockchain tokens in a fun and educational way. This project is designed for demo purposes, competition entries, or learning web3 UX design.

---

## Demo Features

### 1. Wallet Integration
- Connect any **Ethereum-compatible wallet** (MetaMask, etc.).
- View **connected account address**.
- Read **Zen Token (ZTC) balance** from the blockchain.
- All data is **read-only**, no real transactions are required.

### 2. Faucet Simulation
- New users can request **test ZTC tokens** from a configurable faucet.
- Designed to **pay minimal game fees** for demo purposes.
- Includes clickable **faucet button** and **external faucet link**.

### 3. Mini-Game — Spin for Zen
- Simulated **spinner game**: spend ZTC to try and win more.
- Rewards include **0, 0.1, 1, or 2 ZTC**, simulating real betting mechanics.
- Local **high-score tracking** using `localStorage`.
- Fully **client-side**, with optional hooks for real smart contract integration.
- Spinner displays **animated rewards** and updated balances.

### 4. Token Info Panel
- Shows **Zen Token contract address**.
- Displays **connected wallet address**.
- Supports **multi-line overflow** for long addresses.
- Reads **token decimals** and **balance** dynamically.

### 5. Quick Controls
- **Read ZenChain documentation**.
- Open **token on ZenTrace explorer**.
- Request **faucet tokens**.

### 6. Footer & Social Links
- Links to official ZenChain platforms using **social media icons**:
  - X: [https://x.com/zen_chain](https://x.com/zen_chain)
  - Discord: [https://discord.com/invite/zenchain](https://discord.com/invite/zenchain)
  - Telegram: [https://t.me/ZenchainAnnouncements](https://t.me/ZenchainAnnouncements)
  - Website: [https://www.zenchain.io/](https://www.zenchain.io/)
  - GitHub: [https://github.com/zenchain-protocol](https://github.com/zenchain-protocol)

---

## Tech Stack

- **HTML5 / CSS3 / JavaScript**
- **Ethers.js v5.7.2** (Web3 interaction)
- Responsive **CSS Grid and Flexbox**
- No backend required for demo; faucet and blockchain reads simulated or external.

---

## Getting Started

### Prerequisites
- MetaMask or any Ethereum-compatible wallet installed in your browser.
- Modern browser (Chrome, Edge, Firefox recommended).

### Running Locally
1. Clone this repository:
```bash
git clone https://github.com/yourusername/zenchain-demo.git

NOW,
2. Open index.html in your browser.
3. Click Connect Wallet to see your wallet address and ZTC balance.
4. Use Spin for Zen to simulate mini-game rewards.
5. Use Quick Controls to read docs or request test tokens.

File Structure:
├── index.html        # Main demo page
└── README.md         # Project overview and instructions

Notes

The demo is fully client-side and uses a simulated faucet for testing.
The spinner is enhanced with rewards animation and local storage for high scores.
Can be easily upgraded to real on-chain gameplay with smart contract integration.
Compatible with ZenChain official network and ZenTrace explorer.

Contributing

Fork the repository.
Make improvements or feature additions.
Submit a pull request for review.

License
MIT License — feel free to use and adapt this demo for learning, competitions, or prototyping.

ZenChain Links:
X	https://x.com/zen_chain
Discord	https://discord.com/invite/zenchain
Telegram	https://t.me/ZenchainAnnouncements
Website	https://www.zenchain.io/
GitHub	https://github.com/zenchain-protocol
