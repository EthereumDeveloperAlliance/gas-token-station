# Gas Token Station

A smart contract wallet for GasToken management.

# Abstract

To help Etheruem blockchain users manage on-going gas costs the Gas Token Station smart wallet will be developed to easily purchase and use gasTokens.

https://gastoken.io/

The smart wallet should be as minimal as possible. At first only allowig the management of GasTokens and enabling low-cost transactions from an externally owned account (EOA) i.e. private key.

# Introduction

The project uses the https://github.com/austintgriffith/scaffold-eth repo to create a development environment.

Originally the config files were set to `solc` 0.6.6 however the original GasTokens were set to `solc` 0.4.10 so build was environment was updated to allow compiling of the smart contracts for a testing environment.

# Requirements

- [ ] Minimal Viable Smart Wallet
  - [ ] Manage GasTokens
    - [ ] Purchase GasTokens
    - [ ] Free GasTokens
  - [ ] Forward Transations from EOA (externally owned account)
- [ ] Minimal Viable User Interface
  - [ ] Display GasToken Balance
  - [ ] Transaction History

# Discovery

- [ ] Smart Wallet w/ External Permissions
  - [ ] Trigger purchase of GasTokens from external account.
