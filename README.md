# Hardhat Template

This has the hardhat packages and configuration I like to use, with pieces taken from various projects including Uniswap and Sushiswap.

It uses prettier and solhint for linting and typechain to generate TS classes for contracts.

## Set up

See .env.example for environment configuration variables.

Be sure to change the package name in package.json and run `rm -rf .git`.

## Scripts

`yarn test`

Runs all tests in `test/`

`yarn coverage`

Runs all tests with solidity-coverage and generates a coverage report.

`yarn compile`

Compiles artifacts into `artifacts/` and generates typechain interfaces in `typechain/`

`yarn lint`

Runs solhint against the contracts.