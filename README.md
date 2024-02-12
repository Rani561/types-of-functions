# AssetToken 

## Introduction
The `AssetToken` contract is a Solidity smart contract built on the Ethereum blockchain. It provides functionalities for managing an ERC20 token, allowing minting, burning, and transfer of tokens. Additionally, it includes features such as initialization control and token transfer restriction.

## Features
- **Token Initialization**: The contract can be initialized by the architect to enable functionality and mint initial tokens.
- **Token Minting**: Tokens can be minted by the architect and distributed to specified addresses.
- **Token Burning**: Users can burn their tokens, reducing the total token supply.
- **Token Transfer**: Users can transfer tokens to other addresses, subject to transfer allowance.
- **Token Balance Inquiry**: Users can check the balance of tokens in their accounts.
- **Transfer Restriction**: The architect can disable token transfers if needed.

## Usage
1. **Token Initialization**: Call the `initiateToken` function to enable token functionality and mint initial tokens.
2. **Token Minting**: The architect can mint tokens for specified addresses by calling the `mintTokens` function.
3. **Token Burning**: Users can burn their tokens by calling the `burnTokens` function, specifying the amount to burn.
4. **Token Transfer**: Users can transfer tokens to other addresses using the `transferTokens` function, subject to transfer allowance.
5. **Balance Inquiry**: Users can check their token balance by calling the `getAccountBalance` function.
6. **Transfer Restriction**: The architect can disable token transfers by calling the `disableTransfer` function.

## License
This contract is licensed under the MIT License. 
