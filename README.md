# 🏥 Healthcare Records Smart Contract

A secure and decentralized healthcare records management system built on the Educhain blockchain. This smart contract allows authorized healthcare providers to store and access patient records efficiently, ensuring data privacy and security.

## 🛠 Tech Stack

- **Solidity** (Smart Contract Development)
- **Remix IDE** (Smart Contract Deployment & Testing)
- **React** (Frontend Interface)
- **HTML, CSS, JavaScript** (UI Development)
- **MetaMask** (Ethereum Wallet for Transactions)

## ⚙️ Functions

### 🔹 `getOwner()`

- **Description:** Returns the address of the contract owner.
- **Use:** Helps in identifying the deployer of the contract.

### 🔹 `authorizeProvider(address provider)`

- **Description:** Grants authorization to a healthcare provider.
- **Use:** Only the owner can call this function to add trusted providers who can manage records.

### 🔹 `addRecord(uint256 patientID, string memory patientName, string memory diagnosis, string memory treatment)`

- **Description:** Adds a new patient record.
- **Use:** Authorized providers can add medical records securely.

### 🔹 `getPatientRecords(uint256 patientID)`

- **Description:** Retrieves patient records based on their ID.
- **Use:** Only authorized providers can access patient medical histories.

## 🏥 Application Working

This smart contract facilitates secure and decentralized storage of patient healthcare records:

1. The contract owner (deployer) can **authorize** multiple healthcare providers.
2. Only **authorized** providers can add patient records.
3. Each patient record includes **record id, diagnosis, treatment, and timestamp**.
4. Authorized providers can **retrieve patient records** using the unique patient ID.
5. Unauthorized users **cannot** access or modify patient data, ensuring security.

## 🚀 Future Scope

1. **Integration with IPFS** - Store patient records securely on a decentralized file storage system.
2. **Patient Access Control** - Allow patients to view and control their own medical records.
3. **Interoperability with Other Healthcare Systems** - Enable seamless integration with existing hospital databases.
4. **Enhanced Security Measures** - Implement multi-factor authentication for healthcare providers.
5. **AI-Based Analysis** - Utilize AI to analyze patient records for better diagnosis and treatment recommendations.

## 🎥 Video Demonstration
https://drive.google.com/file/d/1-fCeaWCPiANv49SJqLiGFUgIOF1wKdlV/view?usp=sharing

*(https://drive.google.com/file/d/1WJbMMUB-gBLADcMwxjS7VU7IWmaS-rFr/view?usp=sharing)*

