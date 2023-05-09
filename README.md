# Decentralized Banking System (DeFi Bank)
This repository focuses on development of a decentralized banking system which is a DApp built on Ethereum blockchain with smart contract on solidity.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/202927689-6c3fe287-09aa-44d3-ae40-82f1e53f7765.png">
</p>

DeFi Bank provides Witdraw, borrow and payoff fucntionalities. All the data and business logic are stored and run on Ethereum blockchain by smart contracts.


Decentralized Banking Use Cases

Some of the popular DeFi use cases, namely:
- Borrowing and Lending.
- Monetary banking services.
- Decentralized marketplaces.
And, in this study, DeFi Bank provides borrowing and lending which are implemented on solidity with smart contracts.

## DeFi Bank Capabilities
Here are three main functionalities of DeFi Bank provides. Witdraw, borrow and payoff are provided for now but the functionalities will be improved day by day.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/202927223-abe54161-75a8-4b26-b80d-9a8d37c188d6.jpg">
</p>

## Installation

### Setup

- **Node.js**

      sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      nvm install 12.18.3
      node -v

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).

- **MetaMask** installation guide can be found in [here](https://metamask.io/).

### Commands

- Install necessarily Node.js packages

      npm install

- Deploy smart contracts to the Ethereum blockchain

      truffle migrate --reset
      
- Deploy and run the front-end application

      npm start run
      
- Run the scripts to issue tokens

      truffle exec scripts/issue-tokens.js
