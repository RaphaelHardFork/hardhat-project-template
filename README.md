# HardHat Project Template

## Incoming

- exemple for upgradable contract tests and deployment

## Dependency installed:

- openzeppelin (with upgradable contracts and pluggins)
- docgen
- dotenv
- prettier & eslint
- hardhat-gas-reporter
- hardhat-contract-sizer

## Config for networks

- BSC (mainnet & testnet)
- Polygon (mainnet & testnet)

## File template:

- Contract.sol (smart contract intro)
- Contract-test.js (tests syntax initiated)
- Deployment Scripts
- Post deployment scripts

## To do:

Create a `.env` with:

- INFURA_PROJECT_ID
- PRIVATE_KEY

## Node 17 error

Run this command in case of this error:

```
error:03000086:digital envelope routines::initialization error
```

In the terminal:

```
export NODE_OPTIONS=--openssl-legacy-provider

```
