# EXAMPLE CONTRACT

This Solidity program is a simple contract that demonstrates the basic functionality of using `require()`, `assert()`, and `revert()` statements to enforce conditions and handle errors on the Ethereum blockchain. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to understand how to use these statements effectively.

## DESCRIPTION

This program is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract includes functionalities to set a value, ensure only the owner can set the value, and demonstrate how to use `require()`, `assert()`, and `revert()` statements. This program serves as a foundational introduction to error handling and condition enforcement in Solidity, and can be expanded upon for more complex projects in the future.

### Key Functions:
- **Constructor:** Sets the contract deployer as the owner.
- **requireExample:** Allows the owner to set a value, ensuring the value is greater than 20.
- **assertExample:** Ensures the value is greater than 0 using `assert()`.
- **revertExample:** Demonstrates the use of `revert()` to always revert with a error message.

## Executing the Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

### Steps:
1. Copy the contract code into a new Solidity file in Remix.
2. Compile the contract using the Solidity compiler.
3. Deploy the contract to the Ethereum virtual machine (EVM) using Remix.
4. Interact with the deployed contract using the provided functions.

## Authors

Metacrafter Chris  
[@metacraftersio](https://twitter.com/metacraftersio)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
