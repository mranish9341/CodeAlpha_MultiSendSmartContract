# CodeAlpha_MultiSendSmartContract
# Multi-Send Smart Contract

## Overview

The Multi-Send Smart Contract is a Solidity-based blockchain application that enables users to distribute Ether to multiple Ethereum addresses in a single transaction. The contract receives Ether through a payable function, divides the amount equally among all recipient addresses, and securely transfers the funds while verifying each transaction's success.

## Features

* Accepts an array of Ethereum recipient addresses
* Receives Ether through a payable function
* Distributes Ether equally among all recipients
* Verifies successful transfers using low-level calls
* Emits events for transaction tracking
* Deployable and testable on Remix IDE

## Smart Contract Functions

### sendEther(address payable[] recipients)

Receives Ether and distributes it equally among all recipient addresses provided in the array.

### getContractBalance()

Returns the current Ether balance stored in the smart contract.

## Technology Stack

* Solidity ^0.8.20
* Ethereum Blockchain
* Remix IDE

## How to Run

1. Open Remix IDE.
2. Create a file named `MultiSend.sol`.
3. Paste the smart contract code.
4. Compile using Solidity version 0.8.20.
5. Deploy the contract using Remix VM.
6. Enter recipient addresses and Ether value.
7. Execute the `sendEther()` function.

## Example

Recipients:

0xAddress1
0xAddress2

Ether Sent:

1 ETH

Distribution:

0.5 ETH to each recipient

## Project Structure

```
CodeAlpha_MultiSendSmartContract/
│
├── MultiSend.sol
├── README.md
└── .gitignore
```

## Learning Outcomes

This project demonstrates:

* Solidity smart contract development
* Payable functions
* Ether transfer mechanisms
* Event logging
* Array handling in Solidity
* Blockchain transaction validation

## Author

Kundan Kumar Vishwakarma 

## Internship

CodeAlpha Blockchain Development Internship
