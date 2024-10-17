# Create a Token
The Solidity program is a simple program that demonstrates the process of creating tokens using the Solidity programming language.
The purpose of this program is to serve as hands-on experience for someone who wants to understand and implement the fundamentals of token creation on the Ethereum blockchain.

## Description
This program is a simple contract written in Solidity, a programming language designed for creating smart contracts on the Ethereum blockchain.
The contract features two functions: one for minting tokens and the other for burning them. Both functions require two inputs: an address and a non-negative value.
This program provides a clear and simple explanation of token creation on the blockchain.

## Getting Started

### Executing program
To run this program, you can utilize Remix, an online IDE for Solidity. Start by visiting the Remix website at https://remix.ethereum.org/.

Once there, create a new file by clicking the "+" icon in the left sidebar. Save this file with a .sol extension (e.g., `solidityCreateToken.sol`). Next, find the file named `solidity_CreateToken.sol` in this project and copy the code from it into the newly created file on Remix.

To compile the code, navigate to the "Solidity Compiler" tab on the left sidebar. Ensure the "Compiler" version is set to "0.8.18" (or another compatible version), and then click the "Compile solidityCreateToken" button.

After deploying the contract, you can interact with it by using the mint and burn functions. Click on the "MyToken" contract in the sidebar, then select the mint function. You will need to provide an address and a nonnegative value to use this function, and then click the "transact" button to execute the minting process. 

For burning tokens, select the burn function and similarly input an address and nonnegative value. After that, click the "transact" button to begin burning tokens. Using the mint function increases the total token supply, while the burn function decreases it. You can check the total supply by clicking the "totalSupply" button.


## Authors
Lance Benedict F. Feticio

202110075@fit.edu.ph
