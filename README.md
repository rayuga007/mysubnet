# Vault Smart Contract

This smart contract, named `Vault`, is designed to act as a secure and transparent storage facility for ERC20 tokens on the Ethereum blockchain. The contract allows users to deposit tokens into the vault, where they are converted into shares representing ownership in the vault. These shares can later be redeemed to withdraw the deposited tokens.

## Features

- **Deposit Functionality:** Users can deposit ERC20 tokens into the vault, converting them into shares proportional to their contribution relative to the total supply of shares.
- **Withdrawal Functionality:** Users can withdraw deposited tokens by redeeming their shares, receiving an amount of tokens proportionate to the shares redeemed.
- **Safe Storage:** Deposited tokens are securely stored within the contract and can only be withdrawn by the user who initially deposited them.
- **Transparency:** The contract maintains transparency by publicly exposing the total supply of shares and the balance of each user.

## Structure

- **Vault Contract (`Vault.sol`):** This file contains the main logic of the vault smart contract, including deposit, withdrawal, share minting, and burning functions.
- **ERC20 Interface (`IERC20.sol`):** An interface defining the standard ERC20 token functions required for interacting with ERC20-compliant tokens.

## How to Use

1. **Deploy the Contract:** Deploy the `Vault` contract on the Ethereum blockchain, passing the address of the ERC20 token that you want to store in the vault.
2. **Deposit Tokens:** Use the `deposit` function to deposit ERC20 tokens into the vault. Specify the amount of tokens to deposit.
3. **Withdraw Tokens:** Use the `withdraw` function to withdraw previously deposited tokens. Specify the number of shares to redeem.

## License

This smart contract is licensed under the MIT License, which grants users the freedom to use, modify, and distribute the code for both commercial and non-commercial purposes, subject to the conditions specified in the license.

## SPDX-License-Identifier

The SPDX-License-Identifier tag is included at the beginning of each contract file, specifying the license under which the code is released. In this case, the MIT License is used.

## Author

Faizan khan 

rehankhan786khan2011@gmail.com
