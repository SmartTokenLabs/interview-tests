# Test exercise Web3 technology Developer

The following exercise is to create a Web3 Application based on Smart Token Labs - Token Negotiator & three.js - periodic table example https://threejs.org/examples/css3d_periodictable.html. 

The test is split into 4 areas shown below and designed to be submitted after 3 days of development, where to succeed, it's not mandatory to complete all of the task items (please note: no costs should be incured completing this task, completing Web3 related tasks using testnets and testnet tokens).

Best of luck from the Smart Token Lab team! 

## Part 1 - Creating the main application:

- Create a new Github project (public or can be shared directly to the STL team).
- Locate the three.js periodic table example code online.
- Add a new particle formation to the example called 'starfield'.
- On load of the example, the elements should initialise the 'starfield formation', placing the elements randomly at x, y, z positions.
- Adjust the input data structure of the example to include an: image source and clickable URL.
- Use mock images in place of the periodic table elements (the images can be of any anything you choose e.g. placeholder kitty images).
- When the application loads the formation of elements should animate from "Startfield" to "Sphere".
- Push the changes so far to github under the commit name, 'part 1 - complete' with any additional details you wish to add.

## Part 2 - Web3 SetUp

- Create a new web3 Wallet with AlphaWallet (IOS, Android).
- Mint some NFT's (ERC721's) to your wallet via the user interface https://testnets.opensea.io/ or you can do this programatically https://docs.opensea.io/docs/getting-started 
- If changes we made to your github repo e.g. you created an NFT collection programmatically, push the channges with the commit name, 'part 2 - complete' with any additional details you wish to add.

## Part 3 - Integration with Token Negotiator

- Install the token negtoiator into your website (https://www.npmjs.com/package/@tokenscript/token-negotiator).

````html 
  <script type="text/javascript" src="./token-negotiator-dist/negotiator.js"></script>
  <link rel="stylesheet" href="./token-negotiator-dist/theme/style.css" />
````

- Using the Token Negotiator documentation, configure the application so that it can locate the NFT's you have created once your wallet is connected.
- Make adjustments to the NFT images load, instead of the mock images from part 1.
- Push the changes so far to github under the commit name, 'part 3 - complete' with any additional details you wish to add.

## Part 4 - Finishing touches & submission:

- Add any CSS styling to the Dapp / finishing touches.
- Add a README to the GitHub repository including steps to serve and test the application.
- Push the changes so far to github under the commit name, 'part 4 - complete' with any additional details you wish to add.
- Reach out the STL team sharing the link to the GitHub repository.

### web3 resources (these may help during the exercise by are not required for use):

https://goerlifaucet.com/ - tokens for Goerli testnet
https://remix.ethereum.org/ - a great web IDE to debug and deploy Smart Contracts 
https://docs.openzeppelin.com/contracts/4.x/wizard - Smart Contract wizard
https://github.com/TokenScript/token-negotiator-demo-token-minter/blob/main/example.sol - Example ERC721 Smart Contract


