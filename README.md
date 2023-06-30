# MyToken Solidity Contract

This is a Solidity contract named `MyToken` that represents a basic token implementation. The contract allows for minting and burning tokens, and keeps track of the total supply and individual balances.

## Requirements

The contract fulfills the following requirements:

1. The contract has public variables to store the details about the token, including its name (`tokenName`), abbreviation (`tokenAbbr`), and total supply (`totalSupply`).
2. The contract includes a mapping (`balance`) that associates addresses with their token balances.
3. The `mint` function increases the total supply by a specified number of tokens and adds the corresponding amount to the balance of the sender's address.
4. The `burn` function works in the opposite way of the `mint` function. It reduces the total supply and deducts the specified amount from the balance of the sender's address.
5. The `burn` function includes conditionals to ensure that the sender's balance is greater than or equal to the amount intended to be burned.

## Usage

To use this contract, you can follow these steps:

1. Deploy the `MyToken` contract on the Ethereum network.
2. Interact with the contract by calling its functions.
   - Call the `mint` function to create new tokens and assign them to an address.
   - Call the `burn` function to destroy existing tokens from an address.
3. Use the public variables `tokenName`, `tokenAbbr`, and `totalSupply` to retrieve information about the token.
4. Access the `balance` mapping to check the token balances of different addresses.

Please note that deploying and interacting with a smart contract requires familiarity with the Ethereum blockchain and a suitable development environment or client, such as Remix or Truffle.

## License

This contract is released under the MIT license.
