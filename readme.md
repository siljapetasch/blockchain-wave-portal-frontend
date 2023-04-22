# Blockchain Wave Portal

## Project Description
Blockchain Wave Portal is a decentralized application (dApp) developed as part of the Buildspace "Intro to Solidity: Ship an Ethereum dApp" course. The dApp allows users to interact with a smart contract deployed on the Avalanche Fuji testnet, enabling them to send waves along with personalized messages.

## Main Features
- Send waves to the smart contract on the Avalanche Fuji testnet.
- Attach a personalized message with each wave.
- View the list of waves and messages sent by users.

## Technologies and Languages
- Solidity: Smart contract programming language.
- Hardhat: Ethereum development environment for compiling, testing, and deploying smart contracts.
- React: Front-end library for building user interfaces.
- JavaScript: Programming language used for scripting front-end and back-end.
- Avalanche: Blockchain platform for deploying smart contracts and dApps.

## Installation and Setup Instructions

1. Clone the repositories:

```sh
git clone https://github.com/siljapetasch/blockchain-wave-portal.git
git clone https://github.com/siljapetasch/blockchain-wave-portal-frontend.git
cd blockchain-wave-portal
```

2. Install the required dependencies for deploying the contract:

```sh
npm install
```

3. Deploy the smart contract to the Avalanche Fuji testnet:

```sh
npx hardhat run scripts/deploy.js
```

3. Install the required dependencies for the frontend:

```sh
cd ../blockchain-wave-portal-frontend
npm install
```


## Usage Instructions

1. Start the local development server:

```sh
npm start
```

2. Open your browser and navigate to `http://localhost:3000`.

3. Connect your wallet (e.g., MetaMask or Core) to the Avalanche Fuji testnet.

4. Click the "Wave at me" button to send a wave and add a personalized message.

5. View the list of waves and messages sent by other users.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)