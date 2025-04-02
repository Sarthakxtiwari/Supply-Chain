## Project Description
This project implements a **Supply Chain Management System** on the blockchain. The system allows users to:
- **Create a shipment** and assign it to a receiver.
- **Track all instances** of an order during transit.
- **Ensure transparency and security** using smart contracts.
- **Future Improvements**: Integrate AI for **product checking and maintenance** to enhance efficiency and reliability.

## Deployed Contract
- **Network**: Sepolia Testnet
- **Contract Address**: [0x452Fd85F4eB75D6399c5102F414f1ddFf095A814](https://sepolia.etherscan.io/address/0x452Fd85F4eB75D6399c5102F414f1ddFf095A814)

## Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- npm or yarn
- Hardhat
- MetaMask (for interacting with the frontend)

## Smart Contract Deployment

### 1. Setup Environment Variables
Create a `.env` file and add the following:
```
SEPOLIA_RPC_URL=<your-infura-or-alchemy-url>
PRIVATE_KEY=<your-wallet-private-key>
```

### 2. Compile the Contract
```bash
npx hardhat compile
```

### 3. Deploy to Sepolia Testnet
```bash
npx hardhat run scripts/deploy.js --network sepolia
```

## Running the React Frontend

1. Navigate to the frontend directory:
```bash
cd frontend
```
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm start
```
The app will be available at `http://localhost:3000`.

## Interacting with the Contract
The frontend interacts with the deployed smart contract using Web3.js or Ethers.js. Ensure MetaMask is connected to the Sepolia network.

## Additional Resources
- [Sepolia Etherscan](https://sepolia.etherscan.io/)
- [Hardhat Documentation](https://hardhat.org/docs/)
- [React Documentation](https://react.dev/)

## License
This project is licensed under the MIT License.

# Supply-Chain
