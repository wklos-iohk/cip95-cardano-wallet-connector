# CIP-95 Cardano DApp Wallet Connector

Corresponding CIP-95 commit: [197a814](https://github.com/cardano-foundation/CIPs/pull/509/commits/197a814aed897ae8682c083602c131cc16654ab8).

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) from a fork of [dynamicstrategies/cardano-wallet-connector](https://github.com/dynamicstrategies/cardano-wallet-connector).

### React JS demo

In the project directory, you can run: `npm start run`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


### What is this useful for:
You can use this code as a starting point for the following:
- Testing CIP-95 wallet implementations
- Playing with Conway Ledger era features.
- you are building a DApp and want to connect to the user's wallet (Nami, CCVault, or Flint)
- you want to read the balance, the UTXOs and the available tokens at the user's wallet
- you want the user to interact with your DApp

This boilerplate code was written in javascript and React Js, so caters to the devs who already use this framework.

### How does it work:
- It uses the wallet connector standard CIP30, CIP95 and the cardano-serialization-lib
- the CIP30 standard has been implemented by Nami, CCvault and Flint
- It uses the cardano-serializatioon-lib to build transactions in the javascript front-end, then sign them and send the transactrons with the user's wallet
- you can clone the git repo and then `npm install` and `npm start run` to start a local session

### Live Demo

A demo showcasing all functionalities of the wallet connector:

https://ryun1.github.io/cip95-cardano-wallet-connector/