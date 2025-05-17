# BlockFund - Blockchain-based Crowdfunding Platform

**BlockFund** is a decentralized crowdfunding platform that merges blockchain technology with social networking. Built on the **Ethereum blockchain**, BlockFund allows users to raise and support funds securely, transparently, and without centralized control. It empowers donors by recognizing their support and enabling funding for artists, projects, and humanitarian causes.

---

## 🚀 Why Blockchain-Based Crowdfunding?

- **Decentralization**: No central authority controls the platform. Users can fund and launch campaigns independently.
- **Transparency & Security**: Blockchain is a decentralized ledger where all transactions are verifiable, making it easy to validate the legitimacy of a campaign.
- **No Minimum Contribution**: Contributors can support campaigns with any amount they choose.
- **Real-Time Monitoring**: Blockchain enables real-time tracking of funds and campaign progress.
- **Immutable Records**: Campaign data and transactions cannot be altered once recorded.
- **DApps**: BlockFund runs as a decentralized application with zero downtime and resistance to fraud or censorship.

---

## 🛠️ Technologies Used

- **Smart Contracts**: [Solidity](https://soliditylang.org/)
- **Frontend**: JavaScript, [React.js](https://reactjs.org/), [Tailwind CSS](https://tailwindcss.com/)
- **Blockchain Tools**:
  - [Thirdweb](https://thirdweb.com/): Used to create, deploy, and manage the dApp on the Ethereum blockchain.
  - [Hardhat](https://hardhat.org/): Ethereum development environment for smart contract development and deployment.
- **Test Network**: Deployed on the **Sepolia** testnet.

---

## ⚙️ Installation & Setup

Follow these steps to install and run BlockFund locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Prasad0245/BlockFund.git
   ```

2. **Navigate to the Web3 (Smart Contract) Directory**

   ```bash
   cd BlockFund/web3
   ```

3. **Install Dependencies**

   ```bash
   npm install
   ```

4. **Navigate to the Client Directory**

   ```bash
   cd ../client
   ```

5. **Install Frontend Dependencies**

   ```bash
   npm install
   ```

6. **Start the Development Server**

   ```bash
   npm run dev
   ```

7. Open your browser and visit: [http://localhost:5173](http://localhost:5173)

---

## 🧑‍💻 How to Use

To interact with BlockFund:

- Install the [MetaMask](https://metamask.io/download/) browser extension (available for Chrome, Firefox, Edge, and Brave).
- Connect MetaMask to the **Sepolia Testnet**.
- Fund your wallet with test ETH via a Sepolia faucet.
- You can now:
  - **Create a campaign**
  - **Donate to campaigns**
  - **Track donation stats and campaign progress**

---

## 🌟 Features

- **Interactive Forms**: Simple UI for campaign creation and donations.
- **Real-Time Campaign Tracking**: View amount raised, days left, and total donations.
- **Multiple Campaign Cards**: Browse and interact with campaigns created by various users.
- **Request Approval Feature**: Enhances trust between campaigners and donors.
- **Donation History**: Provides transparency and accountability.

---

## 📌 Challenges Overcome

- Migration from **Goerli** to **Sepolia** testnet.
- Sepolia integration issues with Ethereum nodes.
- Adapting to updates and deprecated standards in Web3 while adding new DApp functionality.

---

## 📂 Project Structure

```
BlockFund/
│
├── web3/            # Smart contracts and blockchain scripts
│   └── contracts/
│   └── scripts/
│   └── hardhat.config.js
│
├── client/          # Frontend React app
│   └── src/
│   └── public/
│   └── tailwind.config.js
│
└── README.md
```

---

## 📎 Credit & Inspiration

This project was inspired by open-source blockchain crowdfunding DApps and adapted to align with a social-networking and transparency-focused vision for BlockFund.
