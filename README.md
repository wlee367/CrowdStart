# CrowdStart
A Kickstarter clone (dApp) built with a framework of React JS called Next.JS that leverages the Ethereum network with Solidity smart contracts.

This project uses on the contract/ethereum side: 

1. Solidity version 0.4.17 and the solidity compiler
2. web3.js (Ethereum JavaScript API)
3. Mocha for testing 
4. Truffle-Hdwallet-provider && Ganache-cli (truffle for help to leverage metamask as provider/digital wallet, ganache-cli for testing)
5. Infura API to connect to the network and deploy contract

To deploy a modified version of the contract within this repo:
```
node compile.js
node deploy.js
```

On the webapp side:
1. Next.Js (a framework version of react that comes with serverside rendering)
2. Semantic Ui React for quick styling 

To run the webapp:
```
npm run dev

navigate to localhost:3000
```
Please make sure you have Metamask chrome extension installed to view this application. 
Within this application you can: 

1. create a new "campaign" which will actually deploy a new instance of the campaign contract on the Ethereum Test network
2. View stats such as the address of the manager, the minimum contribution needed to contribute to the campaign, the number of requests the owner of the campaign makes, number of approvers, and campaign balance (aka how much money they received in "funding" so far
3. Create Requests as the owner of the campaign that other users can approve
4. view the requests of each campaign

To develop this project, I followed https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/learn/v4/overview




