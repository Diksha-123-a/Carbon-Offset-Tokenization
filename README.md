# 78. Carbon Offset Tokenization

## 📖 Project Description
This project implements a Soroban smart contract to tokenize and register carbon offset certificates. Each certificate represents a verified amount of carbon dioxide (CO2) that has been removed or avoided through environmental projects like reforestation, renewable energy, or conservation efforts.

## 🌍 Project Vision
To bring transparency, accountability, and traceability to the carbon offset market by tokenizing carbon certificates on-chain. This ensures tamper-proof records, open verification, and easier trading or retirement of carbon credits.

## ✨ Key Features
- **Issue Certificate:** Allows verified issuers to create and register carbon offset certificates.
- **Certificate Lookup:** Fetch detailed information about issued certificates by ID.
- **Immutable Ledger:** Secure and permanent record of offset transactions on the blockchain.

## 📜 Contract Details

### Contract Address: CD5HB6T44AJWL2BLXVTZBCB7PW7S2F3OIAZCHJIQWIRP6MXLSE7XP2ZI
![image](https://github.com/user-attachments/assets/4336afa1-a760-4cc5-acb2-bf418b296805)


| Function             | Description                                                              |
|----------------------|--------------------------------------------------------------------------|
| `issue_certificate`  | Registers a new carbon offset certificate with project name and tonnage. |
| `get_certificate`    | Retrieves the details of a registered certificate using its ID.          |

---

🛠 Built using [Soroban SDK](https://soroban.stellar.org/docs), for transparent and decentralized environmental impact tracking.
