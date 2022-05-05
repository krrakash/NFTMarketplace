# NFT Marketplace

## Skills & Tools

- Solidity for writing Smart Contracts.
- React for UI.
- [Ethers](https://docs.ethers.io/v5/) is used to interact with Blockchain
- [Hardhat](https://hardhat.org/) is used for Development Framework
- [Ipfs](https://ipfs.io/) is used for Metadata storage
- [React routers](https://v5.reactrouter.com/) is used for Navigational components

## Requirements For Initial Setup
- [NodeJS](https://nodejs.org/en/)
- [Hardhat](https://hardhat.org/)

## Setting Up
### 1. Clone/Download the Repository
### 2. Install Dependencies:
```
$ cd NFTMarketplace
$ npm install
```
### 3. Boot up local development blockchain
```
$ npx hardhat node
```
### 4. Migrate Smart Contracts
`npx hardhat run src/backend/scripts/deploy.js --network localhost`

### 5. Run Tests
`$ npx hardhat test`

### 6. Launch Frontend
`$ npm run start`

License
----
MIT

