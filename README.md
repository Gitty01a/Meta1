# Smart Contract - AMAN PRATAP SINGH Token

## Overview

The `Smart` contract is a simple implementation of an ERC-20-like token with minting and burning functionalities. It allows for the creation of a token named "AMAN PRATAP SINGH" with the abbreviation "AMAN". The contract keeps track of the total supply of tokens and the balance of each address.

## Contract Details

- **Token Name**: AMAN PRATAP SINGH
- **Token Abbreviation**: AMAN
- **Version**: Solidity ^0.8.16

## Functions

### `mint(address a, uint x)`

- **Description**: Mints `x` number of tokens to the address `a`.
- **Parameters**:
  - `address a`: The address to which tokens will be minted.
  - `uint x`: The number of tokens to mint.
- **Example Usage**:
  ```solidity
  contractInstance.mint(0xAddress, 1000);
