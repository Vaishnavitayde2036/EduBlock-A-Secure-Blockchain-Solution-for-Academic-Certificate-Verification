# EduBlock: A Secure Blockchain Solution for Academic Certificate Verification

**EduBlock** is a decentralized application designed to authenticate academic certificates using blockchain technology. By leveraging the immutable and decentralized features of blockchain, EduBlock ensures that certificates are tamper-proof, transparent, and easily verifiable by employers, academic institutions, and other stakeholders.

---

## 🚀 Features

* **Immutable Records**: Once a certificate is issued, its record on the blockchain is permanent and cannot be altered or deleted.
* **Easy Verification**: Verifiers can check certificate authenticity without intermediaries or manual processes.
* **Decentralized Storage**: Reduces risk of central database failures and data breaches by using IPFS.
* **User-Friendly Interface**: Intuitive UI for institutions to issue certificates and for employers to verify them.

---

## 🛠️ Technologies Used

* **Frontend**: React.js
* **Backend**: Node.js, Express.js
* **Blockchain**: Ethereum, Solidity
* **Smart Contracts**: Deployed using Truffle Suite
* **Storage**: IPFS (InterPlanetary File System) for storing certificate files
* **Authentication**: JWT (JSON Web Tokens)
* **Database**: MongoDB

---

## 📂 Project Structure

```
EduBlock-Academic-Certificate-Verification/
├── client             # Frontend React application
├── api                # Backend Express server
├── contracts          # Solidity smart contracts
├── migrations         # Truffle migration scripts
├── test               # Smart contract tests
├── uploads            # Uploaded certificate files
├── .gitignore
├── README.md
├── package.json
└── truffle-config.js
```

---

## ⚙️ Setup Instructions

### 🧰 Prerequisites

* Node.js and npm installed
* Truffle Suite installed globally (`npm install -g truffle`)
* Ganache CLI or Ganache GUI for local Ethereum blockchain
* MongoDB installed and running locally

### 🔧 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Vaishnavitayde2036/EduBlock-A-Secure-Blockchain-Solution-for-Academic-Certificate-Verification.git
cd EduBlock-A-Secure-Blockchain-Solution-for-Academic-Certificate-Verification
```

2. **Install backend and root dependencies:**

```bash
npm install
```

3. **Install frontend dependencies:**

```bash
cd client
npm install
cd ..
```

4. **Compile and deploy smart contracts to the local blockchain:**

```bash
truffle compile
truffle migrate
```

> 💡 Make sure Ganache is running before migrating.

5. **Start the backend server:**

```bash
npm run server
```

6. **Start the frontend application:**

```bash
cd client
npm start
```

---

## 📜 License

This project is licensed under the MIT License.

