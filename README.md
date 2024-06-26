# AdiToken

This project implements a basic ERC20 token contract called AdiToken for minting and burning tokens.

## Description

AdiToken is a simple ERC20 token implemented in Solidity. It allows for minting new tokens to specified wallets and burning tokens from existing balances. The contract keeps track of token balances for each address and maintains the total token supply.

## Getting Started

### Installing

To use this contract, you'll need:
* Solidity compiler (version 0.8.0 or higher recommended)
* Ethereum development environment (e.g., Remix, Truffle, Hardhat)
* online Ethereum development environemts are also available

### Executing program

Follow these steps to deploy and interact with the contract:

1. **Compile the Contract**: Use the Solidity compiler to compile `MyToken.sol`.
   solc MyToken.sol --bin --abi --optimize -o ./build
  
2. **Deploy the Contract**: Deploy the compiled contract using your preferred Ethereum development tool or framework.

3. **Interact with the Contract**: Use a web3 provider or an Ethereum wallet like MetaMask to:
   - Mint tokens to an address:
     MyToken.mint(walletAddress, amount, { from: deployerAddress });

   - Burn tokens from an address:
     MyToken.burn(walletAddress, amount, { from: deployerAddress });

## Help

For any issues or questions, please consult the [Solidity documentation](https://docs.soliditylang.org/) or Ethereum developer forums.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
