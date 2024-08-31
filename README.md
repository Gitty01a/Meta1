# Smart Contract - MANASVI Token

## Overview

The `Smart` contract is a simple implementation of an ERC-20-like token with minting and burning functionalities. It allows for the creation of a token named "MANASVI" with the abbreviation "MNV". The contract keeps track of the total supply of tokens and the balance of each address.

## Contract Details

- **Token Name**: MANASVI
- **Token Abbreviation**: MNV
- **Version**: Solidity ^0.8.26

## Functions

### `mint(address a, uint x)`

- **Description**: Mints `x` number of tokens to the address `a`.
- **Parameters**:
  - `address a`: The address to which tokens will be minted.
  - `uint x`: The number of tokens to mint.
- **Example Usage**:
  ```solidity
  contractInstance.mint(0xAddress, 1000);
