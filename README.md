# Fake Product Identification System Using Blockchain

## Overview

The Fake Product Identification System leverages blockchain technology to authenticate products and combat counterfeiting. By integrating a decentralized ledger, the system ensures the integrity and immutability of product information, making it easy to verify the authenticity of products at any point in the supply chain.

## Features

- **Decentralized Ledger**: Uses blockchain technology to store and verify product information.
- **Product Authentication**: Allows users to verify the authenticity of products.
- **Tamper-Proof Records**: Ensures that once data is recorded, it cannot be altered or deleted.
- **Transparency**: Provides transparent access to product history for all stakeholders.

## Technology Stack

- **Blockchain Platform**: Ethereum
- **Smart Contracts**: Written in Solidity
- **Blockchain Integration**: Remix IDE
- **QR Code Storage**: Pinata (IPFS)
- **Backend**: Node.js 
- **Frontend**: React.js 
- **Database**: MySQL 

## Prerequisites

- Node.js (v14.x or higher)
- npm (v6.x or higher)
- Pinata (for QR code storage)
- Remix IDE (for smart contract development)
- MetaMask (for interacting with the blockchain)
- MySQL (for backend database)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/siripujitha01/fake-product-identification-system.git
    cd fake-product-identification-system
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Setup blockchain:**
   - Develop and deploy your smart contracts using Remix IDE.
   - Connect Remix to a local blockchain (Web3.js).

4. **Configure environment variables:**
    Create a `.env` file in the root directory and add your configuration settings.
    ```env
   REACT_APP_API_KEY = pinata_apikey
   REACT_APP_SECRET_KEY = pinata_secretKey
    ```

5. **Run the application:**
    ```sh
    npm start
    ```
    
## Contributing

We welcome contributions to enhance the Fake Product Identification System. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.
    
## Usage

1. **Register a Product:**
   - Access the product registration page.
   - Enter product details (e.g., product name, employee id, manufactured company...).
   - Generate and upload a QR code to Pinata.
   - Submit to store the information on the blockchain.

2. **Verify a Product:**
   - Access the product verification page.
   - Scan the QR code.
   - Retrieve and view the product's blockchain record to verify authenticity.

## Contact

For any questions or inquiries, please contact:

- **Gmail** - siripujithadanaboyina9701@gmail.com
- **GitHub** - siripujitha01
