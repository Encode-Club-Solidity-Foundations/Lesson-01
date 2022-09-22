# Lesson 1 - Introduction
## Wallets and transactions
* What is a wallet
* What wallets are out there
* Using metamasks
* Creating a public-private key pair
* Connecting to Goerli testnet
* Funding via a Faucet
* Sending a ETH transaction
## How ethereum works
* Explaining Etherscan
* Transactions
* Gas
* Blocks
* Consensus and finality
* State changes
* The EVM
* Accounts
## Trying it out
* How uniswap works (briefly)
* See contract on etherscan (briefly)
* Make a swap
## Contract interaction: Token Swap
* What is a state change inside a smart contract operation
## Hands on - Remix
* Remix interface (overview)
### References
https://remix-ide.readthedocs.io/en/latest/
## Coding HelloWorld.sol
* Solidity philosophy
* OOP basics of Solidity
* Contract Structure
  * SPDX License Identifier
  * Pragmas
  * Imports
  * Comments
  * Contract definition
* Variables
* Storage areas
  * Account storage
  * Memory
  * Stack
* Constructor function
* Functions
* Visibility
* Typing
* Return values
### Code Reference
<pre><code>// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.7.0 <0.9.0;
contract HelloWorld {

    constructor() {}

    function helloWorld() public view returns (string memory) {}
   
}
</code></pre>
### References
https://docs.soliditylang.org/en/latest/

## Compiling and deploying
* Compilation parameters
  * Compiler version
  * EVM Version
  * Optimization
* Bytecode
* ABI
* Deployment parameters
  * Environment
  * Account
  * Gas
  * Contract
* Attaching
* Deploying

# Homework
* Create Github Issues with your questions about this lesson
* Read introduction and topics table from references
