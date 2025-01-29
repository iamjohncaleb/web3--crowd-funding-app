# Web3 Crowdfunding App  

This is a **decentralized crowdfunding platform** built on **Ethereum (or any EVM-compatible blockchain)** using **Next.js, Hardhat, and Thirdweb**. The platform allows users to create and fund campaigns transparently on the blockchain, ensuring security and trust in crowdfunding.

---

## 🚀 Features  

- **Decentralized Campaigns**: Users can create fundraising campaigns recorded on-chain.  
- **Smart Contract Integration**: Secure and transparent transactions using Solidity smart contracts.  
- **Wallet Authentication**: Connect with MetaMask, Coinbase Wallet, or WalletConnect.  
- **Thirdweb Integration**: Smart contract deployment and interaction made easy.  
- **Real-time Funding Updates**: Live tracking of campaign progress and contributions.  
- **Responsive UI**: Optimized for both mobile and desktop users.  

---

## 🛠 Tech Stack  

- **Frontend**: [Next.js](https://nextjs.org/), React, Tailwind CSS  
- **Blockchain & Smart Contracts**: Solidity, Hardhat, Thirdweb  
- **Wallet & Blockchain Interaction**: Wagmi, ethers.js, Thirdweb SDK  
- **Backend (Optional)**: IPFS for decentralized file storage  

---

## 📦 Installation & Setup  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/web3-crowdfunding.git
cd web3-crowdfunding
```

### **2. Install Dependencies**  
```bash
npm install
# or
yarn install
```

### **3. Set Up Environment Variables**  
Create a `.env.local` file in the root directory and add the following:  
```plaintext
NEXT_PUBLIC_THIRDWEB_CLIENT_ID=your_thirdweb_client_id
NEXT_PUBLIC_ALCHEMY_API_KEY=your_alchemy_api_key
NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=your_walletconnect_project_id
PRIVATE_KEY=your_deployer_wallet_private_key
```

### **4. Deploy Smart Contracts (Using Hardhat & Thirdweb)**  

#### Compile and Deploy Contracts Locally  
```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
```

#### Deploy to a Testnet/Mainnet (e.g., Goerli, Polygon)  
```bash
npx hardhat run scripts/deploy.js --network goerli
```

### **5. Start the Development Server**  
```bash
npm run dev
# or
yarn dev
```
Visit [http://localhost:3000](http://localhost:3000) in your browser.  

---

## 📂 Folder Structure  
```plaintext
├── components    // UI Components (Navbar, Footer, CampaignCard)
├── contracts     // Solidity smart contracts
├── pages         // Next.js pages (Home, Campaigns, CreateCampaign)
│   ├── api       // API Routes (if needed)
│   ├── index.js  // Homepage
├── scripts       // Deployment scripts for Hardhat
├── styles        // Global and component-specific styles
├── utils         // Helper functions and constants
└── README.md     // Project documentation
```

---

## ✅ Smart Contract Overview  

**Campaign.sol** (Solidity Smart Contract):  
- Allows users to create and contribute to campaigns.  
- Tracks the total amount raised and contributors.  
- Only the campaign owner can withdraw funds.  

---

## 🔗 Deployment & Hosting  

- **Smart Contracts**: Deployed on Ethereum/Polygon via Thirdweb  
- **Frontend Hosting**: Vercel, Netlify, or IPFS  
- **Database (Optional)**: IPFS, Arweave for decentralized data storage  

---

## 👥 Contributing  

1. Fork the repository.  
2. Create a new feature branch.  
3. Make changes and commit.  
4. Submit a pull request.  

---

## 📜 License  

This project is licensed under the **MIT License**.  

---

## 📞 Contact  

- **Author**: Daniella Obiagwuna  
- **Email**: [your-email@example.com](mailto:your-email@example.com)  
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)  

---

Would you like to add any additional sections or details? 😊
