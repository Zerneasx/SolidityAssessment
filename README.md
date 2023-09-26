Solidity Contract
Introduction
The Solidity contract is like a basic example that shows how to make a computer program using Solidity. This program can create and remove tokens and keep track of how many tokens different people have. It's a good starting point for learning how to make and use these special programs on Ethereum.

Getting Started
To work with the MyToken contract, you can follow these steps:

Clone this repository to your local machine or use Remix, an online Solidity IDE.

If using Remix:

Go to the Remix website at https://remix.ethereum.org/.
Create a new file with a .sol extension (e.g., MyToken.sol).
Copy and paste the content of the MyToken.sol contract into the file.
Compile the contract:

In Remix, go to the "Solidity Compiler" tab.
Set the "Compiler" version to 0.8.18 (or another compatible version).
Click the "Compile MyToken.sol" button.
Deploy the contract:

In Remix, go to the "Deploy & Run Transactions" tab.
Select the "MyToken" contract from the dropdown menu.
Click the "Deploy" button.
Interact with the contract:

You can now interact with the deployed contract using the provided functions, such as mint and burn.

Public Variables
tokenName: The name of the token ("META").
tokenAbbrv: The token abbreviation ("MTA").
totalSupply: The total supply of tokens.
Functions
mint(address _address, uint _value): Mint new tokens and increase the balance of an address.
burn(address _address, uint _value): Burn tokens and decrease the balance of an address, with validation to ensure the address has sufficient tokens.
