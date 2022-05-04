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
### 4. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  

### 5. Migrate Smart Contracts
`npx hardhat run src/backend/scripts/deploy.js --network localhost`

### 6. Run Tests
`$ npx hardhat test`

### 7. Launch Frontend
`$ npm run start`

License
----
MIT

