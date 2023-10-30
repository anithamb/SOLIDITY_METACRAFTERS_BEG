# Metacrafters Solidity BeginnerEVM Project1_Create token
This is a learning project in solidity of Metacrafters.io. Solidity is a high-level programming language designed for implementing smart contracts. This simple program teachs  how to create, mint, and burn tokens in solidty.


## Description
This project includes a SolidityToken.sol file in which MyToken contract is written in Solidity version 0.8.18. 
This program is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a mainly Two function that are "Mint" and "Burn" function, which is used to mint and burn the values. There are public variables like string, uint, etc, and even has the mapping of addressses to balances.

### Executing Program
This project can be run using solidity compiler. I have used Remix website at the https://remix.ethereum.org/ for compiling and deploying the contract. After successfully compliling and deploying the contract tokenName, tokenAbbr and tokenSupply variables can be called to get token name 'TECHMB', token abbreviation 'TECM' and total token supply which is 0 initially. Call the mint function providing the address and value to increase the total token supply and balance of the specified token address. Call the burn function providing the address and value to decrease the total token supply and balance of the specified token address. Burn function will be executed only if sufficient balance is available in address. Call the tokenSupply variable to confirm the changes in the total taken suupy after calling the mint and burn functions.

## Requirements
   1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
   2. Your contract will have a mapping of addresses to balances (address => uint)
   3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
   4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
   5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
## Authors
 AnithaMB//
 Metacrafter
https://academy.metacrafters.io/
