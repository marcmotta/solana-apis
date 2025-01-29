# Solana APIs

This repository provides a collection of APIs for interacting with the Solana blockchain.

## Getting Started

To use these APIs, you will need to have a Solana node running. You can find instructions on how to set up a Solana node [here](https://docs.solana.com/developing/get-started/installation).

Once you have a Solana node running, you can install the `solana-apis` package using npm:

```bash
npm install solana-apis
Usage
To use the APIs, you will need to create a new instance of the Solana class:

JavaScript

const { Solana } = require('solana-apis');

const solana = new Solana({
  nodeUrl: 'http://localhost:8899', // Replace with your Solana node URL
});
Once you have created an instance of the Solana class, you can use the various methods to interact with the Solana blockchain. For example, to get the balance of an account, you can use the getBalance method:

JavaScript

const balance = await solana.getBalance('YOUR_ACCOUNT_ADDRESS');
API Reference
The following is a list of the available APIs:

getBalance(address)
getAccountInfo(address)
getProgramAccounts(programId)
sendTransaction(transaction)
For more information on each API, please refer to the Solana documentation.
