# Test excersise for Advanced Javascript Developer

The following exercise is to create a Dapp based on three.js's, periodic table example https://threejs.org/examples/css3d_periodictable.html. 

The test is split into 4 areas shown below and designed to be submitted within 2 days, where to succeed, it's not mandatory to complete all of the task items.

- best of luck from the STL's team! Also reach out if you have any questions as you go.

## Part 1 - Creating the main 3D Web App:

- Locate the three.js periodic table example code online
- Add a new particle formation to the example called 'starfield'.
- On load of the example, the elements should initialise the 'starfield formation', placing the elements randomly at x, y, z positions.
- Adjust the input data structure of the example, so each element added to the application contains / or references an image URL, Description, Title & External URL.
- Load mock images in place of the periodic table elements (the images can be of any anything you choose e.g. placeholder kitty images).
- Add main button which shows when the page loads, with the text "Connect". 
- When clicking "Connect", the formation should animate from "Startfield" to "Sphere".

## Part 2 - Library integration and unit tests:

- Taking the current example you have built, integrate it into your favourite library/framework (Vue, React, Angular, Svelte, or another of choice).
- Add a unit test library such as Jest to the example code and include some initial tests to ensure that the application is working as expected.

## Part 3 - Connect to a wallet:

It's highly recomeneded at this point to use a new Chrome browser Profile / to ensure you don't mix up the wallet used in this exercise with your own.

- Import the demo wallet into MetaMask (details provided to you from Sunil)
- Add the testNet Mumbai / Polygon to MetaMask
- Add an asyc function to the Connect button event, so when clicking connect - the first step connects to a wallet via MetaMask, before animating to the starfield
- Connect the example to a provided Wallet address with MetaMask, showing the NFT's in place of the mock images inside the Dapp.
- Within the meta of the NFT's are URLs, enrich the token data, so when a token is clicked on it will open inside a new window.

## Part 4 - Finishing touches & submission:

- Add a README to the github repository, including the steps to serve and test the application
- Reach out to Sunil sharing the link to the github repository of the code. 











