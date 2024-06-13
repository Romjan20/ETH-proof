This repository contains the Solidity smart contract code for the MyToken cryptocurrency. MyToken is a basic ERC20 token with minting and burning functionalities.
Table of Contents:

   1. Introduction
   2. Requirements
   3. Contract Details
   4. Usage
   5. Contributing
   6. License

Introduction:

MyToken is a simple ERC20 token that allows minting and burning of tokens. It includes functionalities to manage the total supply and individual balances of addresses.
Requirements

The contract fulfills the following requirements:

   1. Public variables to store token details (name, symbol, total supply).
   2.Mapping of addresses to token balances.
   3. Mint function to create new tokens and increase balances.
   4.Burn function to destroy tokens and decrease balances.
   5.Conditional checks in the burn function for sufficient balance.

Contract Details

    Token Name: EtherRise Coin (ERC)
    Solidity Version: >=0.6.12 <0.9.0
    License: MIT

Usage

To use the contract, deploy it on an Ethereum-compatible blockchain. The contract provides functions to mint new tokens and burn existing tokens. Ensure that the conditions for burning tokens are met to avoid errors.
Contributing

Contributions to improve or extend the functionality of this contract are welcome. Please follow the GitHub workflow for contributions, including forking the repository, creating a new branch, making changes, and submitting pull requests.
License

This project is licensed under the MIT License - see the LICENSE file for details# ETH-proof
