# CaritoSwap
## Decentralized Exchange(DEX) on Polygon(Matic) Blockchain

If you wanna try some magic head over to:



## CaritoSwap core contracts
CaritoSwap core contracts are the fork of [Uniswap V2](https://github.com/Uniswap/uniswap-v2-core)

CaritoSwap/Uniswap-V2 contracts are non-upgradeable and hence immutable in nature

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

# Addresses and Verified Source Code:

Mumbai Testnet
- CaritoSwapFactory: https://mumbai.polygonscan.com/address/0x4cab5791640c439d7aece517d70bfefca4b0fb6b
- CaritoSwapRouter: https://mumbai.polygonscan.com/address/0x90d4e9eb792602aa7a7506b477b878307c35e24a

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

## Changes from Uniswap V2

Not even a single line of code has been changed in the core contracts when compared with Uniswap V2. Hence no changelog.

## CaritoSwap periphery contracts

This repository has been forked from [UniswapV2](https://github.com/Uniswap/uniswap-v2-periphery)

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

# CaritoSwap Interface

An open source interface for CaritoSwap -- a protocol for decentralized exchange on Polygon.

Enabling users to:

- Add and remove their liquidity positions on CaritoSwap protocol
- Swap tokens on CaritoSwap protocol

Future Plans:

- Add and remove their liquidity positions on CaritoSwap protocol
- Swap tokens on CaritoSwap protocol

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

start the development server
```sh
yarn dev

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```