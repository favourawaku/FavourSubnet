Creating an EVM-Subnet on Avalanche


Overview


This project establishes an EVM Subnet on the Avalanche network named "mySubnet," featuring its native token, GamersTokens (MTS). The network seamlessly integrates with MetaMask, enabling the deployment and interaction with smart contracts through the injected provider on Remix.


Project Features
These project will be interacting with two smart contracts an ERC20 token and a vault contract, these contracts should be able to:

Token Creation: Deploy your own ERC-20 token with customizable details such as name, symbol, and decimals.

Token Transfers: Users can transfer tokens to other addresses with ease, following the widely adopted ERC-20 standard.

Token Minting: The contract owner has the ability to mint new tokens, expanding the total token supply.

Token Burning: Users can burn their own tokens, reducing the overall token supply etc.

Getting Started
Follow these steps to get the project up and running on your local machine.

Prerequisites

- Node.js and npm installed on your machine.

  
  Clone the repository using the command - git clone https://github.com/username/projectname.git


  Change directory into your project file - cd projectname


  Install all dependencies with - npm install


  Compile the contract using Hardhat - npx hardhat compile


  Run deployment script- npx hardhat run scripts/deploy.js


  Tools Used


  Unix Computer (MacOS or Linux)


  Solidity


  Remix/Hardhat


  Metamask


  Web Browser


  Author


  Favour Sabo


  License
  
  This project is licensed under the [mily] License - see the LICENSE.md file for details
