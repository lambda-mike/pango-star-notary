# Pangolin Star Token

Solution to the first Ethereum project from the Blockchain Developer Nanodegree Program. Boilerplate code was provided and has not changed.

1. Libraries versions:

  - Truffle v5.1.28 (core: 5.1.28)

  - openzeppelin-solidity 2.1.2

2. ERC-721 Token Name: "Pangolin Star Token"

3. ERC-721 Token Symbol: "PST"

4. “Token Address” on the Rinkeby Network: 0xf5c2A3908356430b2B1922E47Ba2C660A248B4e5

## Installation

  - create file _.secret_ with the private key from MetaMask
  - fill in infura key appropriately in _truffle-config.js_
  - run `npm install`
  - run `npm install openzeppelin-solidity@2.1.2`
  - run `npm install truffle-hdwallet-provider`

## Testing

Ensure there is a development server running on: HTTP://127.0.0.1:7545

Adjust the port if needed.

The app was tested using Ganache from truffle suit.

  - `truffle compile`
  - `truffle migrate --reset --network development`
  - `truffle test --network development`
