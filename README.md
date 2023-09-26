# Solidity Contract Assessment
## Description
The MyToken Solidity Project is a basic example that shows how to make a computer program using Solidity. 
This program can create and remove tokens and track how many tokens the user has. 

## Getting Started
To work with the Solidity project, you can follow these steps:
### If using the remix website recommended in the module for online compiler
* Go to the Remix website at https://remix.ethereum.org/.
* Create a new file with a .sol extension
* Copy and paste the content of the MyToken.sol contract into the file.

## Executing the program
### Compile the program
* In Remix, go to the "Solidity Compiler" tab (located on the left side).
* Set the "Compiler" version to 0.8.18 (or press auto-compile).
* Click the "Compile MyToken.sol" button.

### Deploy Transaction
* Go to the "Deploy & Run Transactions" tab in Remix.
* Select the "MyToken" contract from the dropdown menu.
* Click the "Deploy" button.
  
### Setting up the Deployed contract:
* Copy the address(located at Account tab)
* Paste the address on the text boxes, such as in burn, mint, and balance
* You can now use the program that's set up. You can make new tokens or remove some using functions like "mint" and "burn."
### Variables

- `tokenName`: The name of the token (e.g., "META").
- `tokenAbbrv`: The token abbreviation (e.g., "MTA").
- `totalSupply`: The total supply of tokens. The default value is set to 0.

### Functions
- `mint(address _address, uint _value)`: Mint new tokens and increase the balance of an address.
- `burn(address _address, uint _value)`: Burn tokens and decrease the balance of an address, with validation to ensure the address has sufficient tokens.

## Authors
Donato, Zeno.
202011124@fit.edu.ph

## License
This project is licensed under the [Metacrafters] License - see the LICENSE.md file for details
