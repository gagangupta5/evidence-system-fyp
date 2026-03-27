
# EviLedger: Blockchain-Based Digital Evidence System

---

## 1. Overview



---

## 2. Key Features

- Tamper-proof evidence storage using blockchain hashing  
- Secure chain of custody tracking  
- Timestamped evidence records  
- Transparent audit trail  
- Evidence verification using cryptographic hash comparison  
- Secure access for authorized users  
- Off-chain storage for large evidence files  

---

## 3. Technology Stack

### Frontend
- HTML  
- CSS  
- JavaScript  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  

### Security & Blockchain
- Cryptographic Hashing (SHA-256)  
- Blockchain Ledger for evidence storage  

### Tools
- Git & GitHub  
- VS Code  
- Postman  

---

## 4. System Architecture

EviLedger follows a hybrid architecture combining blockchain with off-chain storage.

**          User (Investigator)
                    │
                    ▼
      Web Application Interface
                    │
                    ▼
        Backend Server (Node.js)
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
   Database            Blockchain Layer
  (MongoDB)         (Evidence Hash Ledger)


---

## 5. System Explanation

### 1. Frontend Interface
Investigators upload and manage evidence through a user-friendly web interface.

### 2. Backend Server
Handles authentication, evidence submission, and verification processes.

### 3. Evidence Hashing
Each file is converted into a unique cryptographic hash (digital fingerprint).

### 4. Blockchain Ledger
The hash is stored on the blockchain to ensure immutability.

### 5. Off-Chain Storage
Actual evidence files are stored in the database for efficiency and scalability.

---

## 6. Project Workflow

1. **Evidence Upload**  
   Investigator uploads evidence → system generates hash  

2. **Blockchain Record Creation**  
   Hash + metadata stored on blockchain  

3. **Evidence Storage**  
   Original file stored securely in database  

4. **Chain of Custody Tracking**  
   Every action recorded with timestamp & user ID  

5. **Evidence Verification**  
   Hash is recalculated and compared with blockchain  

---

## 7. Project Structure

eviledge/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   └── models/
│
├── blockchain/
│   └── evidenceLedger.js
│
├── database/
│   └── dbConfig.js
│
└── README.md



---

## 8. Use Cases

- Digital Forensics  
- Cybercrime Investigation  
- Law Enforcement Agencies  
- Legal Evidence Management  
- Secure Document Verification  

---

## 9. Future Improvements

- Smart contract integration  
- IPFS-based decentralized storage  
- Role-based access control  
- Evidence encryption  
- Multi-organization sharing  
- Integration with Ethereum / Hyperledger  

---

## 10. Contributors

- Avani Katiyar  
- Akanksha Dixit  
- Arpit Uttam  
- Gagan Gupta  
- Anurag Pal  
- Abhash Pandey  

---
