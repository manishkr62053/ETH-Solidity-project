# Token Creation 
This readme file provides a step by step guide on how to create a token.
## Overview
This code contract is a Solidity smart contract that defines a token called MyToken with the symbol MX and the name MXP.
It has three public variables: tokenName, abbrv, and totalSupply. 
It also has a mapping variable called balances that maps an address to a uint value.
Finally, it has two functions: mint and burn.
## Public Variables
1)  `tokenName`: string public variable that stores the token name.
2)  `abbrv`: string public variable that stores the token abbreviation.
3)  `totalSupply`: uint public variable that stores the total supply of tokens.
## Mapping variable
`balances`: mapping variable that maps an address to a uint value.
## Mint function 
The mint function is used to add tokens to an address and increases the total supply of tokens.
The mint function takes two arguments: an address _address and a uint _value.
It increases the total supply of tokens by _value and adds _value to the balance of _address.
## Burn function 
The burn function is used to remove tokens from an address and decrease the totalsupply of tokens.
The burn function takes two arguments: an address _address and a uint _value.
It decreases the total supply of tokens by _value and subtracts _value from the balance of _address, but only if the balance of _address is greater than or equal to _value.
## License
MIT pragma solidity 0.8.18;
## Usage
Compile and deploy this contract using Remix Solidity development environment.





