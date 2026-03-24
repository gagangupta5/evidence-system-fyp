# evidence-system-fyp

==OVERVIEW==

Eviledge is a secure digital evidence tracking system designed to maintain the integrity, authenticity, and traceability of forensic evidence using blockchain and cryptographic techniques.
Traditional evidence management systems are vulnerable to tampering, unauthorized access, and lack of transparent audit trails. Eviledge addresses these issues by implementing a decentralized and tamper-proof evidence tracking mechanism where every evidence record is securely stored and verified through blockchain.
The system ensures that the chain of custody is preserved, enabling investigators and legal authorities to track evidence throughout its lifecycle.


==KEY FEATURE==

1 Tamper-proof evidence storage using blockchain hashing
2 Secure chain of custody tracking
3 Timestamped evidence records
4 Transparent audit trail
5 Evidence verification through cryptographic hash comparison
6 Secure access for authorized investigators
7 Off-chain storage for large evidence files


==TECHNOLOGY STACK ==

FRONT-END

HTML,
CSS,
JavaScript


BACK-END

Node.js / Express

DATABASE

MongoDB


SECURITY & BLOCKCHAIN

Cryptographic Hashing (SHA-256),
Blockchain ledger for evidence record storage


TOOLS

Git & GitHub,
VS Code,
Postman


==SYSTEM ARCHIETECTURE== 

The Eviledge system follows a hybrid architecture combining off-chain storage with blockchain verification.



User (Investigator)

        │
        ▼
        
Web Application Interface

        │
        ▼
        
Backend Server (Node.js)

        │
 ┌──────┴────────┐
 ▼               ▼
 
Database      Blockchain Layer
(MongoDB)     (Evidence Hash Ledger)



==EXPLANATION==


1 Frontend Interface
Investigators upload and manage evidence through a web interface.

2 Backend Server
Handles authentication, evidence submission, and verification.

3 Evidence Hashing
Evidence files are processed using cryptographic hashing to generate a unique fingerprint.

4 Blockchain Ledger
The hash of the evidence is stored on the blockchain to create an immutable record.

5 Off-Chain Storage
Actual evidence files are stored in the database or secure storage to optimize performance.


==PROJECT WORKFLOW== 


1. Evidence Upload :
Investigator uploads evidence.
System generates a cryptographic hash of the file.

2. Blockchain Record Creation :
The hash and metadata are stored in the blockchain ledger.

3. Evidence Storage :
The original file is stored securely in the database.

4. Chain of Custody Tracking :
Each action (upload, transfer, verification) is recorded with a timestamp and user ID.

5. Evidence Verification :
When evidence is retrieved, the system recalculates the hash.
The new hash is compared with the blockchain record to confirm authenticity.


==PROJECT STRUCTURE== 

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


==USECASE== 

Eviledge can be used in:

1 Digital Forensics

2 Cybercrime Investigations

3 Law Enforcement Agencies

4 Legal Evidence Management Systems

5 Secure Document Verification


==FUTURE IMPROVEMENTS==

1 Smart contract integration

2 IPFS based decentralized evidence storage

3 Role-based access control

4 Evidence encryption

5 Multi-organization evidence sharing

6 Blockchain network integration (Ethereum / Hyperledger)


==CONTRIBUTORS==

Avani Katiyar

Akanksha Dixit

Arpit Uttam

Gagan Gupta

Anurag Pal 

Abhash Pandey

