# Metamask ATM

## Overview

The Metamask ATM is a decentralized application (dApp) built on the Ethereum blockchain. It allows users to interact with a smart contract that simulates ATM functionality, enabling deposits, withdrawals, and ownership transfer.

## Features

- **User Authentication**: Connects to the user's Ethereum wallet via MetaMask.
- **Deposit Functionality**: Users can deposit any amount of Ether into the contract, which updates their balance.
- **Withdraw Functionality**: Users can withdraw any amount of Ether from the contract, with checks to ensure sufficient balance.
- **Balance Inquiry**: Users can view their current balance in the ATM.
- **Ownership Transfer**: Current owners can transfer ownership to another Ethereum address by entering it into the input field.
- **Responsive UI**: Built with React for a seamless user experience.
- **Error Handling**: Provides feedback on actions and alerts for missing wallet or errors during transactions.

## Prerequisites

- Node.js (v14 or later)
- MetaMask installed in your browser
- An Ethereum test network (e.g., Goerli) account with some test Ether

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/harshit2064/Metamask-ATM.git
   cd Metamask-ATM

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Authors

Harshit Sharma

## License

This project is licensed under the MIT License.
