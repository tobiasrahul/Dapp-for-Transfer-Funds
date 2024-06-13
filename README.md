# Dapp for Transferring funds
This is the project under module 2 of ETH + AVAX PROOF: Intermediate EVM Course from metacrafters. In this project we have to create a simple contract having 2-3 functions and display the values of those functions on frontend.

# Description
This is web3 application named as Rahul Berwal's Funds Transfer created using Solidity, HTML, CSS and Javascript. 
* This application is deployed on Hardhat which is a development environment and testing framework for Etherum Smart Contracts. It complies the contracts and run them on a develpoment network.
* To intreact with Ethereum blockchain ecosytem, Metamask is used in this project. Metamask is a free web and mobile crypto wallet that allow users to store and swap cryptocurrencies.
* Solidity is used to write Smart Contracts. It is a programming language used most for writing smart contracts.

# Getting Started
## Executing Program
### Follow these steps to run this project in your system
1. Download or clone this prject by clicking on code button and from there choose HTTPS url and paste in your terminal and type `git clone https://github.com/tobiasrahul/Eth-Avax-Intermediate-module-2.git eth-avax-module-2`.
2. Open terminal and install dependencies by running command `npm install`.
3. Open additional two terminals in your Vs Code.
4. In the second terminal type `npx hardhat node`.
5. In the third terminal, type `npx hardhat run --network localhost scripts/deploy.js`.
6. Back in the first terminal, type `npm run dev` to launch the front-end.


## Setting Up Metamask Account
1. Download and add Metamask extension in your browser.
2. Open your Metamask account and click on "Setting".
3. In the "Network" section and click on "Add Network".
4. Use Following details to add network:
   * Network Name: hardhat-test-network ( or as you wish like localhost 123)
   * RPC URL: http://127.0.0.1:8545/
   * Chain ID: 31337
   * Currency Symbol: ETH
5. "Save" the Hardhat network to Metamask.

## Import Account to Metmask
1. In Metamask extension, click on account icon.
2. Click on "Import Account".
3. Back to your second terminal in Vs Code and copy private key of Account 0.
4. Paste the key in import account section and your account is successfully connected with 10000 ETH !!!!

# Frontend Execution
1. Type http://localhost:3000/ in your browser and click on "Connect" button. This will connect Metamask to the Hardhat local network.
2. Now you can either change account name or click on Transfer funds to send Ethers to another account.
3. To change the name of your account you have to simply click on "change account name" button and type the new name and confirm it. This will change the name of your account and some gas fee will get deducted from your metamask account.
4. To transfer funds choose any account and copy its address and click on "Transfer Funds" button. Paste the address and amount of ETH you want to transfer and click on Confirm.
5. Pop up window of metamask will be open and your gas fees will be deducted and transaction gets completed.

## Help
If you face any error make sure to check following steps:
1. Make sure you have entered RPC URL correctly.
2. Make sure in index.html file you have correctly linked the js files.
3. You have correctly entered the private key of the hardhat testing accounts.

# Authors
Rahul Berwal [@tobiasrahul](https://github.com/tobiasrahul)

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
