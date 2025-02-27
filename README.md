🦄 Decentralized Portfolio Tracker

🚀 Overview

A Web3-powered portfolio tracker that allows users to connect their MetaMask wallet, fetch real-time crypto balances, and display live market data using the CoinGecko API.

🔥 Key Features

✅ Connects to MetaMask

✅ Fetches crypto balances from the connected wallet

✅ Displays real-time market data (prices, volume, market cap) from CoinGecko API

✅ Stores user info & favorites using Firebase (Firestore)

✅ Responsive Next.js UI with TailwindCSS

Planned Features:
🔹 Multi-chain support (Ethereum, BSC, Solana)
🔹 Transaction history tracking
🔹 Dark mode UI


🛠 Tech Stack

Frontend: React + Next.js + TailwindCSS

Backend: Firebase (Firestore)

Web3 Integration: Ethers.js / Web3.js

Market Data: CoinGecko API



📦 Installation & Setup

1️⃣ Clone the Repository

```sh

git clone https://github.com/YasmnKhalid/web3-portfolio-tracker.git

cd web3-portfolio-tracker
```
2️⃣ Install Dependencies
```sh
npm install
```

3️⃣ Set Up Environment Variables
Create a .env.local file and add:

```sh
NEXT_PUBLIC_INFURA_API_KEY=your_infura_api_key

NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key

NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain

NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id

NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket

NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id

NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id

NEXT_PUBLIC_COINGECKO_API=https://api.coingecko.com/api/v3
```

4️⃣ Run the Development Server

```sh
npm run dev
```

The app will be available at http://localhost:3000

📸 Screenshots (To be added)
NOT YET

🔗 API References
CoinGecko API
Ethers.js Docs
Firebase Firestore


👨‍💻 Author
Yasmin Khalid

GitHub: [YasmnKhalid](https://github.com/YasmnKhalid)


LinkedIn: LinkedIn: www.linkedin.com/in/ysmnkhalid


📜 License
This project is open-source and available under the MIT License.

