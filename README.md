## Ethereum Election Decentralised Application

#### Description
An Election Application based on Ethereum Platform based Blockchain Technology. Once a Person votes, he will not be able to vote again unless the address changes with the help of Metamask Extension.

The Project consists of various folders and files.

1. build/contracts- This folder consists of files that are automatically is made up when we run truffle migrate --reset in the terminal.

2. contracts- This folder consists of files containing smart contracts written in Solidity Programming Language, which is the backend of this Project.

3. migrations- This folder consists of files that help Truffle to run truffle migrate. This folder consists of initial migration, which helps build the build files and deploy contracts, which helps migrate the smart contracts.

4. node_modules- This folder consists of node modules automatically put in whenever we run npm install in our Project Directory.

5. src- This folder consists of code for the Frontend of our decentralised application.
    1) css- This folder contains CSS code for our Frontend to make our Frontend beautiful.
    2) fonts- This folder contains a Configuration for fonts to be displayed.
    3) js- This folder contains JavaScript code that makes our Website a dynamic application, which helps respond to our application.
    4) index.html- This file contains the HTML code of our application, which helps build the skeleton of our Website.

6. test- Whenever we deploy our application, we must check before its deployment as an application involving Blockchain Technology cannot be changed after its deployment. If we can change, it has too much hassle.
This folder contains code for checking errors if they are present so that we prevent them from deploying. We run the truffle test to check errors if they are present and require code written in the test directory.

7. bs-config.json- This file contains code for Configuration, which helps in build files.

8. LICENSE- This file contains the license pertaining to use.

9. package-lock.json- This file is automatically built when we initialise truffle framework in our project directory.

10. package.json- This file is automatically built when we initialise truffle framework in our project directory.

11. truffle-config.json- This file contains Configuration pertaining to how the application will run, its localhost server, etc.

#### Dependencies to run this Project on your personal computer-
1. NPM- https://nodejs.org/

2. Truffle- https://github.com/trufflesuite/truffle

3. Ganache- http://truffleframework.com/ganache/

4. Metaask Extension- https://metamask.io/

#### Steps to run this Project-
1. To clone the Project on your PC-
git clone https://github.com/iamabhayprakash/ethereum-election/

2. Execute npm install inside the ethereum-election directory.

3. Ganache- Start Ganache on your local computer to have a local blockchain network with each account having some ETH in their account.

4. Run truffle migrate --reset to migrate the contracts on your PC from scratch.

5. Configure Metamask on your local PC according to Ganache running with the help of Mnemonic provided uniquely to each instance of Blockchain network running and import an account provided by Ganache.

6. Run npm run dev on the terminal inside the directory having your Project's code, that is, ethereum-election, preferably in Chrome Browser.
