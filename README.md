# ETH+AVAX Assessment Project 2
This project serves as the assessment for the Smart Contract Management lesson of the ETH+AVAX Course.

## Description
This is the README for the Metacrafter ATM smart contract, a simple financial management tool written in Solidity. The contract provides functionality for depositing and withdrawing funds securely.

## Features
- **Deposit Function:**
  - Allows the user to manually input the amount they want to deposit.
  - Allows the owner to securely deposit funds into the account.
  - Verifies that the sender is the owner before processing the deposit.
  - Updates the account balance accordingly.
    
- **Withdraw Function:**
  - Allows the user to manually input the amount they want to withdraw.
  - Permits the owner to securely withdraw funds from the account.
  - Validates ownership and checks if the withdrawal amount is less than the account balance.
  - Updates the account balance accordingly.

- **Check Balance Function:**
 - Provides a read-only method, getBalance, to retrieve the current account balance.

## Authors

Zedric Ramoso
[@r0gueph](https://github.com/r0gueph)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
