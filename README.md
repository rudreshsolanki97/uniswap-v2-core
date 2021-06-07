# Uniswap V2

[![Actions Status](https://github.com/Uniswap/uniswap-v2-core/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-core/actions)
[![Version](https://img.shields.io/npm/v/@uniswap/v2-core)](https://www.npmjs.com/package/@uniswap/v2-core)

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

# Deployments

## Rinkeby

- Factory - 0x60b3e6064576eD2718716769BD876F8229db9B13  
- Token A - 0x4f2D5bF9D39d74587Ed020C2e9dc05f0C4a71FDE  
- Token B - 0xc99Ec6A9ca934cF96af5c8772b77f24BE28C62e6  
- Pair - 0xbbA7393F732748abf45EAB8712aD84E44ED9F3E2  
- WETH - 0x8c54312d1Ba7C42eA7DD7F6504Df9b90De11797D  
- Router V02 - 0xF2FdAc1a05C2e0314d7b4b78C02eC32dBDB57Cc6 

## Rinkeby - Post INIT_CODE_HASH

- Factory - 0x33502267d3B9ACFFEA2D2C39376bF4b6Bf7f83C4  
- Token A - 0xc8633632B4EC3fC556F222f2271767fE926bEAb5  
- Token B - 0x606FF9AeB43EEC89BdfFaC7698282311EB7582fd  
- WETH - 0xa760C28C575019b38B9768EE479B0805a95245B4  
- Router V02 - 0x6FE19EFCBa8a3590f205b9Ea89697aabF7d56e73 
- Pair ( Token A - Token B ) - 0x115505752fDe033CE0C7b8C0A7ab06b7e7B406bF

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`
