# MyToken Solidity Contract

This is a simple Solidity contract called MyToken. It represents a basic ERC20 token implementation with functionalities to mint and burn tokens.

## Contract Details

- Token Name: MARC
- Token Abbreviation: MRC
- Total Supply: 0

## Public Variables

The contract has the following public variables:

- `tokenName`: A string representing the token's name.
- `tokenAbbrv`: A string representing the token's abbreviation.
- `totalSupply`: An unsigned integer representing the total supply of tokens.

## Mapping Variable

The contract uses a mapping variable called `balances` to store the token balances of addresses.

## Functions

### `mint`

```solidity
function mint(address _address, uint _value) public


```
### `burn`
function burn(address _address, uint _value) public
