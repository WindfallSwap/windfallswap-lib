# windfallswap-lib

[![Tests](https://github.com/WindfallSwap/windfallswap-lib/workflows/Tests/badge.svg)](https://github.com/WindfallSwap/windfallswap-lib/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/WindfallSwap/windfallswap-lib/workflows/Static%20Analysis/badge.svg)](https://github.com/WindfallSwap/windfallswap-lib/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/WindfallSwap/windfallswap-lib/workflows/Lint/badge.svg)](https://github.com/WindfallSwap/windfallswap-lib/actions?query=workflow%3ALint)
[![Fuzz Testing](https://github.com/WindfallSwap/windfallswap-lib/workflows/Fuzz%20Testing/badge.svg)](https://github.com/WindfallSwap/windfallswap-lib/actions?query=workflow%3A%22Fuzz+Testing%22)
[![npm](https://img.shields.io/npm/v/@windfallswap/lib)](https://unpkg.com/@windfallswap/lib@latest/)

Solidity libraries that are shared across Windfall Swap contracts. This package focuses on safety and execution gas efficiency.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @windfallswap/lib`

Then import the contracts via:

```solidity
import '@windfallswap/lib/contracts/libraries/Babylonian.sol';

```
