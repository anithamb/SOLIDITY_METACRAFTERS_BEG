# MetacraftersSolidity Beginner Project_Create token
This is a learning project in solidity of Metacrafters.io.

## Description
This project includes a SolidityToken.sol file in which MyToken contract is written in Solidity version 0.8.18. 
This program is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a mainly Two function that are "Mint" and "Burn" function, which is used to mint and burn the values. There are public variables like string, uint, etc, and even has the mapping of addressses to balances.

### Executing Program
This project can be run using solidity compiler. I have used Remix website at the https://remix.ethereum.org/ for compiling and deploying the contract. After successfully compliling and deploying the contract tokenName, tokenAbbr and tokenSupply variables can be called to get token name 'TECHMB', token abbreviation 'TECM' and total token supply which is 0 initially. Call the mint function providing the address and value to increase the total token supply and balance of the specified token address. Call the burn function providing the address and value to decrease the total token supply and balance of the specified token address. Burn function will be executed only if sufficient balance is available in address. Call the tokenSupply variable to confirm the changes in the total taken suupy after calling the mint and burn functions.

## Authors
Metacrafter AnithaMB
https://academy.metacrafters.io/
