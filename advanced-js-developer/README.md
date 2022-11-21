# Test exercise for advanced Javascript Developer

The following exercise is to create a Dapp based on three.js's, periodic table example https://threejs.org/examples/css3d_periodictable.html. 

The test is split into 4 areas shown below and designed to be submitted after a maximum of 3 days of development, where to succeed, it's not mandatory to complete all of the task items.

Best of luck from the Smart Token Lab team! 

## Part 1 - Creating the main application:

- Locate the three.js periodic table example code online
- Add a new particle formation to the example called 'starfield'.
- On load of the example, the elements should initialise the 'starfield formation', placing the elements randomly at x, y, z positions.
- Adjust the input data structure of the example to include an: image URL, description, title & external URL.
- Use mock images in place of the periodic table elements (the images can be of any anything you choose e.g. placeholder kitty images).
- Add a button which shows when the page loads, with the text "Connect". 
- When clicking "Connect", the formation should animate from "Startfield" to "Sphere".

## Part 2 - Library integration and unit tests:

- Taking the current example you have built, integrate it into your favourite library/framework (Vue, React, Angular, Svelte, or another of choice).
- Add a unit test library such as Jest to the example code and include some initial tests to ensure that the application is working as expected.

## Part 3 - Mint some NFTs and Connect to a wallet:

At this point it's highly recommended to use a new Chrome browser Profile / to ensure you don't mix up the wallet used in this exercise with your own.

- Using a demo MetaMask wallet and a test net such as Goerli, mint some NFT's.

This can be done using any of the following paths below; 

- Deploying a smart contract and adding Dapp logic around this example (using tools such as; Web3, ethers, Infura, Alchemy, Solidity, Truffle, Hardhat etc). 

Or

- Minting NFT's via http://testnets.opensea.io/ and using the OpenSea API [https://docs.opensea.io/reference/rinkeby-api-overview ](https://docs.opensea.io/reference/api-overview) to load your tokens from Goerli or any chosen supported testnet.

Laslty...

- Build an async sequence, so the user connects their wallet > the mock tokens leave the page > then the users actual tokens appear in the sphere formation showing the NFT URI images.

## Part 4 - Finishing touches & submission:

- Add any CSS styling to the Dapp / finishing touches
- Add a README to the GitHub repository including the steps to serve and test the application
- Reach out to Sunil sharing the link to the GitHub repository of the code

### web3 resources (these may help during the exercise by are not required for use):

https://goerlifaucet.com/ - tokens for Goerli testnet
https://remix.ethereum.org/ - a great web IDE to debug and deploy Smart Contracts 
https://docs.openzeppelin.com/contracts/4.x/wizard - Smart Contract wizard
https://github.com/TokenScript/token-negotiator-demo-token-minter/blob/main/example.sol - Example ERC721 Smart Contract


