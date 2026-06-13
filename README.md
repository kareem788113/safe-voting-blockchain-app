# Safe Voting Blockchain App

## 📌 Project Overview

Safe Voting Blockchain App is a blockchain-based voting system designed to ensure secure, transparent, and tamper-proof elections.

The system uses Solidity Smart Contracts, Python (Web3.py), and Ganache to allow users to vote securely while ensuring that votes cannot be modified or deleted.

The project implements role-based access control with two user types:

- Admin (Privileged User)
- Normal User (Standard User)

---

## 🎯 Project Objectives

- Prevent vote manipulation.
- Store voting data securely on the blockchain.
- Restrict administrative actions to authorized users only.
- Provide a transparent voting history.
- Implement a custom ERC-20 token for the voting ecosystem.

---

## 🛠 Technologies Used

### Blockchain
- Solidity
- Ganache

### Backend
- Python
- Web3.py

### Cryptography
- Hashing Algorithms (SHA-256)

### Development Tools
- Visual Studio Code
- Git & GitHub

---

## 📂 Project Structure

```text
safe-voting-blockchain-app/
│
├── contracts/
│   ├── SafeVoting.sol
│   └── VotingCoin.sol
│
├── build/
│
├── scripts/
│   ├── deploy.py
│   ├── auto_setup.py
│   ├── admin_dashboard.py
│   ├── live_alert.py
│   ├── data_history_report.py
│   └── balance_snapshot_exporter.py
│
├── app/
│   ├── main.py
│   ├── user_menu.py
│   ├── admin_menu.py
│   ├── transaction_sender.py
│   └── helpers.py
│
├── config/
│   ├── settings.py
│   └── contract_addresses.json
│
├── data/
│
├── docs/
│
├── tests/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 👥 User Roles

### Admin

The Admin has permission to:

- Add new candidates
- Update candidates
- Mint Voting Coins
- Pause the voting system
- Resume the voting system
- Transfer ownership to another admin
- View dashboard statistics

### Normal User

The User can:

- Register a profile
- Vote for candidates
- View voting results
- Check token balance
- Check ETH balance
- View personal activity history

---

## 📜 Smart Contract Features

### SafeVoting Contract

- Candidate Management
- Voting System
- User Registration
- Ownership Management
- Pause / Resume Functionality
- Batch Candidate Operations

### VotingCoin Contract

- ERC-20 Compatible Token
- Admin-only Minting
- Balance Tracking
- Token Transfers

---

## 🔐 Security Features

- onlyOwner Modifier
- Access Control Validation
- Transaction Verification
- Blockchain-Based Audit Trail
- Security Testing Scripts

---

## 📊 Reports & Analytics

The project includes:

- Admin Dashboard
- Voting Statistics Report
- User Activity History
- Balance Snapshot Exporter
- Live Vote Alert System

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/safe-voting-blockchain-app.git
```

### 2. Open Project

```bash
cd safe-voting-blockchain-app
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Start Ganache

Run Ganache and make sure it is listening on:

```text
http://127.0.0.1:7545
```

### 5. Deploy Smart Contracts

```bash
python scripts/deploy.py
```

### 6. Run Application

```bash
python app/main.py
```

---

## 🧪 Testing

Run security and functionality tests:

```bash
python tests/test_pause_resume.py
```

```bash
python tests/ownership_transfer_test.py
```

---

## 📈 Future Improvements

- Graphical User Interface (GUI)
- Mobile Application
- Multi-Chain Deployment
- Advanced Voting Analytics
- Enhanced Cryptographic Verification

---

## 👨‍💻 Team Members

| Name | Role |
|--------|--------|
| Member 1 | Smart Contract Development |
| Member 2 | Blockchain Scripts |
| Member 3 | Terminal Application |
| Member 4 | Testing & Documentation |

---

## 📄 License

This project was developed for educational purposes as part of the Cryptography & Blockchain Course Final Project.
