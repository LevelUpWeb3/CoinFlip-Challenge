# Testing Guide for Level Up Gaming Contracts

This guide explains how to run tests for the smart contracts in the Level Up Gaming project using Foundry.

## Prerequisites

1. Ensure you have Foundry installed. If not, follow the installation guide at [https://book.getfoundry.sh/getting-started/installation](https://book.getfoundry.sh/getting-started/installation).

2. Make sure you're in the project directory (`Levelup-Gaming`).

3. replace your code in (`Levelup-Gaming/CoinFlip-Challenge/src/CoinFlip.sol`) with your finished code.

## Running Tests

To run tests for your contract:

--forge -vvv

## Understanding Test Files

Each contract in the `src` directory has a corresponding test file in the `test` directory:

- `src/CoinFlip.sol` is tested by `test/CoinFlip.t.sol`
