# Solidity Assessment

This program is a Solidity smart contract named MyToken. It is designed to manage a custom cryptocurrency with the following features:

Token Details:

Token Name: "META"
Token Abbreviation: "MTA"
Total Supply: 0 (initially)
Address Balances:

The contract maintains a mapping of Ethereum addresses to token balances.
Mint Function:

The mint function allows for the creation of new tokens. It takes two parameters: an Ethereum address and a value (number of tokens).
It increases the total supply by the specified value and increments the balance of the provided address accordingly.
Burn Function:

The burn function allows for the destruction of tokens. It also takes an address and a value as parameters.
It checks if the balance of the provided address is greater than or equal to the specified value.
If the condition is met, it deducts the value from the total supply and from the balance of the provided address.
