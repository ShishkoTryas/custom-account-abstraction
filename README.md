# Account abstraction tutorial

Code for "Account Abstraction" for zkSync

## Installation and compilation

You need Node.js and npm(or yarn).

## Deployment and usage

Replacing the PRIVATE_KEY with the private key of the Ethereum wallet you're using for development

To run the scripts to deploy and execute the contracts, use the `zksync-deploy` command:

- `npx hardhat deploy-zksync --script deploy-factory.ts`: deploys the factory contract
- `npx hardhat deploy-zksync --script deploy-multisig.ts`: deploys a multisig wallet and executes a transaction.
