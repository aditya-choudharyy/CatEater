MyToken Contract
Overview
MyToken is a simple Solidity smart contract that represents a custom token on the Ethereum blockchain. It allows for minting (creating) and burning (destroying) tokens, along with tracking the total token supply and individual balances.

Contract Details
Name: AdiToken
Symbol: ADI
Total Supply: 0 (initially)
Functions
mint
Description: Creates new tokens and assigns them to a specified address.
Parameters:
wallet: The address to which new tokens will be assigned.
amount: The number of tokens to create and assign.
Access: Public
Effects: Increases the total token supply and updates the balance of the recipient address.
burn
Description: Destroys tokens held by a specified address.
Parameters:
wallet: The address from which tokens will be burned.
amount: The number of tokens to destroy.
Access: Public
Effects: Decreases the total token supply and updates the balance of the burning address. It verifies that the address has sufficient balance before burning the tokens.
Usage
To use this contract:

Deploy it to the Ethereum blockchain using a compatible development environment like Remix or Hardhat.
Interact with the deployed contract using Ethereum wallets or dApp interfaces.
Call the mint function to create new tokens for specific addresses.
Call the burn function to destroy tokens held by specific addresses.
License
This project is licensed under the terms of the MIT License. See the LICENSE file for details.
