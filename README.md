# CaritoSwap
## Decentralized Exchange(DEX) on Celo(Alfajores) Blockchain


## CaritoSwap core contracts
CaritoSwap core contracts are the fork of [Uniswap V2](https://github.com/Uniswap/uniswap-v2-core)
Few changes have been done to transfer half of the protocol fees (i.e 0.025%) to the charity by giving its address in the factory contract so that it automatically transfers the fees to the Charity without any human intervention and without any discrepancy

CaritoSwap/Uniswap-V2 contracts are non-upgradeable and hence immutable in nature

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

## Addresses and Verified Source Code:

Celo(Alfajores) Testnet
- CaritoSwap Factory: https://alfajores-blockscout.celo-testnet.org/address/0xe7F7067C9ECAB27c5F7f13E02b13eD50931f6D0f/transactions
- CaritoSwap Router: https://alfajores-blockscout.celo-testnet.org/address/0x4cAb5791640C439D7Aece517d70BFEfcA4b0Fb6b/transactions
- WCELO (Wrappeed Celo): https://alfajores-blockscout.celo-testnet.org/address/0x524d97A67f50F4A062C28c74F60703Aec9028a94/transactions
- Multicall Contract: https://alfajores-blockscout.celo-testnet.org/address/0x387ce7960b5DA5381De08Ea4967b13a7c8cAB3f6/transactions



## Changes from Uniswap V2

Few changes have been done to transfer half of the Protocol Fees (i.e 0.025% of the Liquidity Token) to the Charity by giving the Charity's address in the factory contract so that it automatically transfers the fees to the Charity without any human intervention and without any discrepancy

## CaritoSwap periphery contracts

This repository has been forked from [UniswapV2](https://github.com/Uniswap/uniswap-v2-periphery)

Some changes have been made to support the automatic transfer of the half of the protocol fees to the Charity



## CaritoSwap Interface

An open source interface for CaritoSwap -- a protocol for decentralized exchange on Celo.

Enabling users to:

- Add and remove their liquidity positions on CaritoSwap protocol
- Swap tokens on CaritoSwap protocol

Future Plans:

- Add the functinality of Farming, Staking and Limit Orders
- Making it live on the Celo Blockchain (coming very soon 😉)

## Deploying the CaritoSwap on local machine

Clone the repository

move into the UserInterface Directory

```sh
cd UserInterface
```

install dependencies using **yarn** or **npm**

```sh
yarn

or

npm install
```
If using Windows then run these two commmands

```sh
rm -r ./node_modules/@uniswap/sdk
```
And Then this command

```sh
cp -r ./forks/@uniswap/sdk ./node_modules/@uniswap/sdk
```

start the development server
```sh
yarn start

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```