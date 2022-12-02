# Getting Started

# New to the repo?

## Step 1: Create hardhat.config.js

If you have just cloned the repo..
Run npx hardhat run scripts/run.js
Create blank hardhat config and follow guidance here: https://buildspace.so/p/build-solidity-web3-app/lessons/deploy-smart-contract-to-testnet

## Step 2: Create artifacts

npx hardhat run scripts/run.js

## Step 3: Run deploy.js on the Goerli network

npx hardhat run scripts/deploy.js --network goerli

# Starting the app

## Step 1: Install packages

cd app, npm i

## Step 2: Start app

cd app, npm start

TODO:
// Make sure you are connected to the Goerli network (otherwise app doesn't)
// Make wave count public / exist on chain - https://buildspace.so/p/build-solidity-web3-app/lessons/storing-messages-from-users-on-blockchain
// Make contract redeployable after making wave count public
// What is run.js doing? Do we need it?
